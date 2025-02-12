**Medical Diagnosis using Probabilistic AI
**
Overview

This repository contains an AI-based medical diagnosis system that utilizes probabilistic reasoning to classify and predict diseases using Bayesian Networks and Gaussian Processes.


Datasets Used:

The project is based on two medical datasets:

Dementia Prediction Dataset – MRI-based dementia classification

Features: Age, MMSE score, CDR, nWBV, eTIV, etc.

Source: Kaggle - Dementia Dataset

Parkinson's Disease Dataset – Voice-based Parkinson’s classification

Features: MDVP:Fo(Hz), Jitter, Shimmer, HNR, RPDE, etc.

Source: Kaggle - Parkinson’s Dataset


Objective

The goal is to infer probabilistic queries such as:

What is the probability of a patient having Dementia given specific MRI features?

What is the probability of a patient having Parkinson's given specific voice attributes?


Tech Stack

Language: Python

Libraries Used:

pandas, numpy (Data Processing)

bnlearn, pgmpy (Bayesian Networks)

scikit-learn (Machine Learning)

matplotlib, seaborn (Visualization)

Gaussian Processes for probabilistic modeling


Implementation Details

Data Preprocessing

  Handled missing values, feature scaling, and discretization.

  Used cross-validation (K=5) to ensure robust model evaluation.

Probabilistic Models Used:

  Discrete Bayesian Networks for categorical features.
  
  Gaussian Bayesian Networks for continuous features.

  Gaussian Processes for probabilistic inference.
  
Performance Evaluation

  Accuracy, AUC (Area Under Curve), Brier Score, and KL-Divergence used as metrics.
  Compared results across different models.
  

Results & Findings

The Bayesian Networks provided high accuracy in probabilistic inference.

Gaussian Processes worked better for continuous data.

Feature importance analysis helped in understanding key attributes affecting predictions.


Author:

Faisal Hussain – MSc Computer Science, University of Lincoln

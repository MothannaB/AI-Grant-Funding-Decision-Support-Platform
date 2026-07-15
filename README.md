# AI Grant Funding Decision Support Platform

## Overview

Organizations that distribute grants often receive thousands of funding applications each year, making manual evaluation a time-consuming and resource-intensive process. This project demonstrates how deep learning can support grant reviewers by predicting the likelihood that an applicant organization will successfully achieve its proposed objectives based on historical funding data.

I developed a deep neural network using TensorFlow and Keras to analyze applicant characteristics and estimate the probability of funding success. The model is designed to serve as a decision-support tool that helps reviewers prioritize applications, identify higher-risk proposals, and make more informed funding decisions.

While this repository focuses on the machine learning component, the model could be integrated into a larger grant management platform to assist foundations, nonprofit organizations, and government agencies during the grant review process.

---

## Business Problem

Grant-making organizations often receive far more applications than they can realistically fund. Reviewing every application manually requires significant time and resources, and maintaining consistency across evaluations can be challenging.

This project addresses that problem by developing a predictive model that analyzes historical grant application data to estimate whether an organization is likely to successfully utilize awarded funding.

The model provides an additional source of information for grant reviewers, helping them identify promising applications while flagging proposals that may require closer evaluation.

---

## Project Objectives

- Develop a deep learning model to predict grant funding success.
- Build a complete machine learning pipeline for data preprocessing, model training, and evaluation.
- Generate probability-based predictions that can support funding decisions.
- Demonstrate how artificial intelligence can improve efficiency within grant review workflows.

---

## Business Workflow

```
Historical Grant Applications
            │
            ▼
Data Cleaning and Preprocessing
            │
            ▼
Feature Engineering
            │
            ▼
Deep Neural Network
            │
            ▼
Grant Success Prediction
            │
            ▼
Decision Support for Grant Reviewers
```

---

## My Role

For this project, I:

- Prepared historical grant application data for machine learning.
- Cleaned and transformed categorical and numerical features.
- Encoded categorical variables for neural network training.
- Standardized input features using Scikit-learn.
- Built a multi-layer deep neural network using TensorFlow and Keras.
- Trained and evaluated a binary classification model.
- Saved the trained model for future inference and deployment.

---

## Dataset

The model predicts whether a grant application is likely to result in a successful funding outcome using historical applicant information.

Example features include:

- Organization type
- Affiliation
- Government classification
- Industry classification
- Income category
- Funding amount requested
- Organizational status
- Special considerations
- Application characteristics

Target variable:

- IS_SUCCESSFUL
  - 1 = Successful funding outcome
  - 0 = Unsuccessful funding outcome

---

## Machine Learning Pipeline

### Data Preparation

- Loaded historical grant application data
- Removed non-predictive features
- Encoded categorical variables
- Split data into training and testing datasets
- Standardized numerical features

### Model Development

- Built a feed-forward deep neural network
- Configured multiple hidden layers using ReLU activation
- Used a Sigmoid activation function for binary classification
- Compiled the model using binary cross-entropy loss and the Adam optimizer

### Model Training

- Trained the model over multiple epochs
- Monitored model performance throughout training
- Saved checkpoints during training

### Model Evaluation

The trained model was evaluated using:

- Binary classification accuracy
- Loss function
- Test dataset evaluation

---

## Technologies Used

### Programming

- Python

### Data Processing

- Pandas
- NumPy

### Machine Learning

- TensorFlow
- Keras
- Scikit-learn

### Data Preparation

- StandardScaler
- Train-Test Split
- One-Hot Encoding

### Model Management

- Model Checkpointing
- HDF5 Model Export

### Development Environment

- Jupyter Notebook

---

## Repository Structure

```
AI-Grant-Funding-Decision-Support-Platform/

│
├── AlphabetSoupCharity.ipynb
├── data/
│   └── charity_data.csv
├── models/
│   └── AlphabetSoupCharity.h5
├── README.md
├── images/
└── requirements.txt
```

---

## Potential Business Applications

This type of predictive model could support organizations such as:

- Nonprofit foundations
- Government grant agencies
- Educational funding organizations
- Research funding institutions
- Corporate social responsibility programs
- Philanthropic investment organizations

Possible use cases include:

- Grant application screening
- Funding risk assessment
- Proposal prioritization
- Decision support for reviewers
- Grant portfolio analysis



## Key Skills Demonstrated

- Deep Learning
- Neural Networks
- Binary Classification
- Data Preprocessing
- Feature Engineering
- Data Standardization
- TensorFlow
- Keras
- Scikit-learn
- Model Evaluation
- Machine Learning Pipeline Development
- Predictive Analytics

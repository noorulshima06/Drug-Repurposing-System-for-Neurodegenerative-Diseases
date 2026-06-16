# Drug Repurposing System for Neurodegenerative Diseases

## Overview

This project is an AI-powered Drug Repurposing System designed to identify potential therapeutic candidates for neurodegenerative diseases such as Parkinson's Disease and Alzheimer's Disease.

The system integrates drug-target interaction data, disease-associated gene datasets, machine learning techniques, similarity analysis, and patient-specific risk assessment to discover promising drug candidates that may be repurposed for neurological disorders.

---

## Objectives

- Identify candidate drugs for Parkinson's Disease and Alzheimer's Disease.
- Analyze drug-gene and disease-gene relationships.
- Rank drugs based on biological similarity and machine learning predictions.
- Support personalized drug recommendations using patient health information.
- Provide visual analytics for drug prioritization.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Gradio

---

## Dataset Sources

The project utilizes multiple biomedical datasets:

### Drug Data
- DrugBank Vocabulary Dataset
- Pharmacologically Active Drug-Gene Interaction Dataset

### Disease Data
- Parkinson's Disease Gene Dataset
- Alzheimer's Disease Gene Dataset

### Patient Data
- Clinical patient information dataset used for personalized risk evaluation.

---

## Methodology

### 1. Data Preprocessing
- Human-specific drug records filtering
- Gene name standardization
- Missing value handling
- Drug ID cleaning and normalization

### 2. Gene Similarity Analysis
The system computes Jaccard Similarity between:

- Drug target genes
- Disease-associated genes

This helps identify drugs sharing biological pathways with neurodegenerative diseases.

### 3. Feature Engineering

Generated features include:

- Total Drug Targets
- Parkinson Overlap Score
- Alzheimer's Overlap Score
- Parkinson Similarity Score
- Alzheimer's Similarity Score

### 4. Machine Learning Prediction

A Logistic Regression model is trained to predict promising drug candidates.

The model performs:

- Training/Test Split
- Feature Scaling
- Probability Prediction
- Candidate Ranking

### 5. Drug Prioritization

Drugs are ranked based on:

- Disease Gene Overlap
- Similarity Scores
- Machine Learning Probability Scores

Top candidate drugs are generated for:

- Parkinson's Disease
- Alzheimer's Disease

---

### 6. Patient-Specific Drug Assessment

The system evaluates:

- Kidney Risk
- Liver Risk
- Diabetes Risk
- Elderly Patient Risk

to provide safer recommendations for individual patients.

---

## Key Features

- Drug-Gene Interaction Analysis

- Disease Gene Matching

- Jaccard Similarity-Based Ranking

- Machine Learning Prediction

- Parkinson's Disease Candidate Discovery

- Alzheimer's Disease Candidate Discovery

- Personalized Risk Assessment

- Interactive Visualization Dashboard

- Gradio User Interface

---

## Visualization

The project generates graphical reports including:

- Top Drug Candidates
- Probability Score Comparisons
- Disease-wise Drug Ranking
- Training and Validation Performance

---

## Results

The system identifies high-potential repurposable drugs by combining:

- Biological similarity analysis
- Disease-gene overlap
- Machine learning prediction scores

This approach helps accelerate drug discovery while reducing development cost and time.

---

## Project Files
DrugRepurpose.ipynb -> Main project notebook,
README.md -> Project documentation.

---

## Future Enhancements

- Deep Learning Models
- Graph Neural Networks
- Real-Time DrugBank Integration
- Clinical Trial Data Analysis
- Multi-Disease Drug Repurposing
- Web-Based Deployment

---

## Author 
Noorul Almaz Shima K

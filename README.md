# Fake Job Posting Detector

Detect fake job postings using machine learning. This project leverages data analysis and various machine learning models to accurately distinguish between genuine and fraudulent job advertisements.

---

## Table of Contents

- [About](#about)
- [Data](#data)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About

In the era of digital recruitment, fake job postings are a significant concern that can lead to financial and security risks for applicants. This project addresses the challenge by employing machine learning techniques to detect fraudulent job postings. The detector is trained on a labeled dataset to analyze various aspects of job advertisements such as text description, company details, and more.

---

## Data

- **Dataset:** The project uses a labeled dataset consisting of job postings, with each entry marked as either genuine or fake.
- **Data Features:**  
  - **Job Title**
  - **Company Name**
  - **Location**
  - **Job Description**
  - **Requirements**  
  Additional features may include posting date, employment type, and industry.
- **Preprocessing:**  
  - Missing values and duplicates are handled.
  - Text data is cleaned and normalized.
  - Feature extraction techniques such as TF-IDF or word embeddings are applied for converting text into numerical features.

---

## Features

- **Data Cleaning & Preprocessing:** Comprehensive cleaning, normalization, and transformation of raw job posting data.
- **Feature Engineering:** Extraction and creation of meaningful features from textual and categorical data.
- **Model Implementation:** Training of multiple classifiers including Logistic Regression, Random Forest, and XGBoost.
- **Evaluation Metrics:** Accuracy, Precision, Recall, and F1 Score to assess model performance.
- **Visualization:** Graphical insights through histograms, box plots, and correlation matrices for understanding data distributions and feature relationships.

---

## Installation

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook (or any other preferred Python IDE)
- Required Python libraries:  
  ```bash
  pip install pandas numpy scikit-learn xgboost matplotlib seaborn nltk

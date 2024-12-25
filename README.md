# Spam Mail Prediction Project

## Overview

This project aims to classify emails as **spam** or **ham** using advanced machine learning techniques. By analyzing email content and patterns, the system provides an automated and efficient way to filter unwanted emails, ensuring a clutter-free inbox.

---

## Features

- **Preprocessing:**  
  Cleans and tokenizes email text to prepare data for analysis.
  
- **Feature Extraction:**  
  Utilizes methods like **TF-IDF**, **bag-of-words**, and **word embeddings** for extracting relevant features.

- **Classification Models:**  
  Implements and compares various algorithms including:
  - Support Vector Machines (SVM)
  
- **Performance Metrics:**  
  Evaluates the models using:
  - Accuracy

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Harsh3202/Spam_mail_Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd spam-mail-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Dataset

Already provided

**Note:** Ensure to preprocess the dataset by removing duplicates and irrelevant columns before training.

---


## Results

- Detailed results and comparisons of different models are available in the `results/` directory.
- The best-performing model achieved:
  - **Accuracy:** 97%
---


## Technologies Used

- **Programming Language:** Python
- **Libraries:** 
  - Pandas, NumPy
  - Scikit-learn, 


---

## Future Work

- Expand feature engineering to include contextual email metadata.
- Incorporate deep learning models like RNNs or Transformers.
- Develop a web-based UI for real-time spam detection.

---

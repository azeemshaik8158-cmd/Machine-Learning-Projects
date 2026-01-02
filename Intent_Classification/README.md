# Utterance Classification using Logistic Regression

## Project Overview
This project focuses on classifying short user utterances (text messages) into meaningful categories using Natural Language Processing (NLP) and Machine Learning. The objective is to build a simple, reliable, and explainable baseline model that can automatically understand text inputs and assign them to the correct class.

This approach is practical for real-world systems like chatbots, virtual assistants, and enterprise automation tools where quick and accurate categorization is required.

---

## Business Objective
Many organizations use conversational systems that continuously receive user text inputs. Handling these manually is inefficient and slow.  
This project helps in:

- Automatically classifying user utterances into relevant categories
- Supporting intent understanding for chatbot and conversational AI systems
- Reducing manual workload and improving response accuracy
- Providing a transparent ML solution suitable for decision-driven environments

---

## Machine Learning Problem
**Problem Type:** Multi-Class Text Classification  
**Input:** User utterances (short text messages)  
**Output:** Predicted category label

---

## Dataset Description
The dataset contains:
- User utterances written in natural language  
- Corresponding labels indicating their category

Such datasets are typically used in:
- Chatbots
- Virtual Assistants
- Customer Support Automation
- Intent Classification Engines

There is also class imbalance, where some categories have more samples than others, which impacts evaluation and model understanding.

---

## Approach

### 1️⃣ Data Understanding & Preprocessing
- Explored dataset structure and label distribution
- Identified class imbalance
- Cleaned and normalized text
- Removed unnecessary noise characters
- Converted text to numerical format using vectorization

### 2️⃣ Feature Extraction
- Used **TF-IDF / Bag of Words** representation  
- Transformed text into feature vectors suitable for machine learning

### 3️⃣ Model Development
- Implemented **Logistic Regression**
- Applied regularization to avoid overfitting
- Chosen specifically for:
  - Strong baseline performance
  - Fast training and prediction
  - Interpretability

---

## Model Evaluation
Evaluated the model using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix (to analyze class-wise performance)

These metrics helped understand how the model behaves across different categories rather than focusing only on overall accuracy.

---

## Key Results
- Logistic Regression delivers strong baseline performance
- Model is lightweight and scalable for real-time inference
- Feature weights help identify important text patterns
- Suitable for production environments requiring transparency and speed

---

## Key Learnings
- Handling multi-class NLP problems
- Working with TF-IDF feature engineering
- Evaluating classification performance beyond accuracy
- Understanding the impact of class imbalance on model behavior

---

## Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Logistic Regression  
- CountVectorizer / TfidfVectorizer  
- Classification Metrics  
- Matplotlib / Seaborn

---

This project strengthened my understanding of practical NLP model development, from preprocessing and feature extraction to model building and evaluation in a real-world context.

# **Disaster Detection Using Tweets**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/downloads/)  
A machine learning-based project that detects disaster-related tweets to aid in disaster response and relief efforts. The project applies Natural Language Processing (NLP) techniques and classification models to analyze tweet data and classify them as disaster or non-disaster.

---

## **Table of Contents**

1. [Project Motivation](#project-motivation)  
2. [Dataset Description](#dataset-description)  
3. [Key Features](#key-features)  
4. [Implementation Details](#implementation-details)  
5. [Model Evaluation](#model-evaluation)  
6. [Setup and Usage](#setup-and-usage)  
7. [Technologies Used](#technologies-used)  
8. [Future Scope](#future-scope)  
9. [Contributions](#contributions)  

---

## **Project Motivation**

Disasters disrupt lives and require immediate attention. Social media platforms like Twitter have become crucial tools for information dissemination during such events. By analyzing tweets in real time, this project aims to:  
- Automate the classification of tweets as disaster-related or not.  
- Support quicker decision-making for disaster response teams.  

---

## **Dataset Description**

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com). It includes labeled tweets, with each tweet tagged as:  
- **1**: Related to a disaster.  
- **0**: Not related to a disaster.

### **Dataset Size**
- **Training Set**: 7,000 tweets  
- **Testing Set**: 3,000 tweets  

### **Attributes**
- `id`: Unique tweet identifier  
- `text`: Content of the tweet  
- `target`: Label (0 or 1) indicating if the tweet is disaster-related  

---

## **Key Features**

- Cleaned and preprocessed tweet data for consistent analysis.  
- NLP-based feature extraction methods, including:  
  - Tokenization  
  - Lemmatization  
  - Stop-word removal  
- Implementation of multiple machine learning models:  
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Naive Bayes  
- Comparative analysis of model performance.

---

## **Implementation Details**

1. **Data Cleaning:**  
   Removed URLs, special characters, and stop words.  

2. **Feature Extraction:**  
   - Used **TF-IDF Vectorizer** to extract meaningful features from the text data.  

3. **Model Training:**  
   - Trained models include Logistic Regression, SVM, and Naive Bayes.  
   - Used 80:20 split for training and testing.  

4. **Evaluation Metrics:**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1 Score  

---

## **Model Evaluation**

| Model                  | Accuracy | Precision | Recall | F1 Score |  
|------------------------|----------|-----------|--------|----------|  
| Logistic Regression    | 77.48%   | 76.75%    | 67.64%  | 71.91%  |  
| SVM                    | 78.69%   | 80.41%    | 65.79%  | 72.37%  |  
| Naive Bayes            | 80.18%   | 82.67%    | 67.64%  | 74.41%  |  

---

## **Setup and Usage**

### **Prerequisites**

- Python 3.8 or above  
- Jupyter Notebook or any Python IDE  

### **Installation**

1. Clone the repository:  
   ```bash
   git clone https://github.com/SrujanBhirud/Disaster-Detection-using-Tweets.git
   cd Disaster-Detection-using-Tweets
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```

---

## **Technologies Used**

- Python  
- Pandas, NumPy (Data Manipulation)  
- Scikit-learn (Machine Learning)  
- Matplotlib, Seaborn (Visualization)  

---

## **Future Scope**

- Integration with real-time Twitter data using the Twitter API.  
- Implementation of deep learning models like LSTMs for enhanced accuracy.  
- Expansion to multilingual disaster detection.  

---

## **Contributions**

Contributions are always welcome!  
Feel free to fork the repository and submit pull requests with improvements, fixes, or new features.

--- 

⭐ **If you found this project helpful, please give it a star!**

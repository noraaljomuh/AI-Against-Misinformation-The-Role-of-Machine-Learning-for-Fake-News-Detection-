# AI Against Misinformation: Fake News Detection Using Machine Learning

This project was developed as part of the **ARTI406 – Machine Learning** course at **Imam Abdulrahman Bin Faisal University**. It implements and evaluates machine learning models for **fake news detection**, aiming to combat misinformation in digital media.

---

## 📌 Project Overview

The system analyzes news article text and predicts whether it is **fake** or **real** based on linguistic and statistical features. Multiple machine learning algorithms were trained and compared to identify the most effective approach for this classification task.

**Key Highlights:**

* **Goal:** Automatically classify news as fake or real.
* **Dataset:** [Fake News Dataset](https://www.kaggle.com/c/fake-news) (Kaggle)
* **Models:** Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, K-Nearest Neighbors
* **Best Accuracy Achieved:** **99.5%** with Logistic Regression
* **Languages & Tools:** Python, scikit-learn, Pandas, NumPy, Matplotlib, NLTK

---

## 🛠 Project Workflow

1. **Data Collection**

   * Kaggle Fake News dataset containing labeled news articles.

2. **Data Preprocessing**

   * Lowercasing text
   * Removing punctuation, numbers, and stopwords
   * Lemmatization and tokenization
   * Handling missing values

3. **Feature Extraction**

   * TF-IDF Vectorization
   * Bag-of-Words representation

4. **Model Training & Evaluation**

   * Tested multiple ML classifiers
   * Evaluated using Accuracy, Precision, Recall, and F1 Score

---

## 📊 Results

| Model               | Accuracy  | Precision | Recall | F1 Score |
| ------------------- | --------- | --------- | ------ | -------- |
| Logistic Regression | **99.5%** | 0.99      | 0.99   | 0.99     |
| Decision Tree       | 99.3%     | 0.99      | 0.99   | 0.99     |
| Random Forest       | 99.3%     | 0.99      | 0.99   | 0.99     |
| Gradient Boosting   | 99.3%     | 0.99      | 0.99   | 0.99     |
| KNN                 | 84.3%     | 0.86      | 0.84   | 0.84     |


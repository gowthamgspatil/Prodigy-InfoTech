#  Task 4 - Sentiment Analysis

**Prodigy InfoTech Data Science Internship**

##  Project Overview

This project is part of my **Data Science Internship at Prodigy InfoTech**.
The objective is to perform **Sentiment Analysis** on Twitter text data to classify tweets into different sentiment categories (such as *positive, negative, neutral*).

The dataset used is `twitter_training.csv`, which contains labeled tweets for training and evaluation.

---

##  Repository Structure

```
│── twitter_training.csv      # Dataset  
│── Sentiment_Analysis.ipynb  # Jupyter Notebook implementation  
│── README.md                 # Project documentation  
```

---

##  Requirements

Install the required Python libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

---

##  Steps in the Notebook

1. **Import Libraries** → Load required Python packages.
2. **Load Dataset** → Read `twitter_training.csv` into Pandas DataFrame.
3. **Data Cleaning & Preprocessing**

   * Remove unwanted characters, hashtags, mentions, links
   * Convert text to lowercase
   * Tokenization & Stopword removal
   * Lemmatization/Stemming
4. **Feature Extraction**

   * Convert text into numerical form using **TF-IDF / CountVectorizer**
5. **Model Building**

   * Train a **Machine Learning classifier** (e.g., Logistic Regression, Naive Bayes, SVM)
   * Predict sentiment labels
6. **Model Evaluation**

   * Accuracy Score
   * Confusion Matrix
   * Classification Report
7. **Visualization**

   * Sentiment distribution plots
   * Word clouds for positive & negative tweets

---

##  Results

* Built a sentiment classification model using Twitter data.
* Key evaluation metrics:

  * **Accuracy Score**
  * **Precision, Recall, F1-Score**
* Visualizations provide insights into tweet sentiment trends.

---

##  How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/prodigy-task4-sentimentanalysis.git
   cd prodigy-task4-sentimentanalysis
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Sentiment_Analysis.ipynb
   ```
3. Run all cells sequentially to reproduce results.

---

##  Internship Info

This project is submitted as **Task 4: Perform Sentiment Analysis on Twitter Data** under the **Prodigy InfoTech Data Science Internship Program**.

---

##  Contact


* **LinkedIn:** [gowthamgshivamurthy](https://www.linkedin.com/in/gowthamgshivamurthy)
* **Gmail:** [gowthamgshivamurthy@gmail.com](mailto:gowthamgshivamurthy@gmail.com)

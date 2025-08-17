#  Task 3 - Decision Tree Classifier

**Prodigy InfoTech Data Science Internship**

##  Project Overview

This project is part of my **Data Science Internship at Prodigy InfoTech**.
The objective is to build a **Decision Tree Classifier** to analyze the **Bank Marketing Dataset** and predict whether a client will subscribe to a term deposit (`yes` / `no`).

The dataset used is `bank-additional.csv`, which contains client and campaign-related attributes from direct marketing campaigns of a Portuguese banking institution.

---

##  Repository Structure

```
│── bank-additional.csv       # Dataset  
│── Decision_tree.ipynb       # Jupyter Notebook implementation  
│── README.md                 # Project documentation  
```

---

##  Requirements

Make sure the following Python libraries are installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

##  Steps in the Notebook

1. **Import Libraries** → Load required Python packages
2. **Load Dataset** → Read `bank-additional.csv` into Pandas DataFrame
3. **Exploratory Data Analysis (EDA)**

   * Check data distribution
   * Handle missing values
   * Encode categorical features
4. **Data Preprocessing**

   * Feature selection
   * Normalization (if required)
   * Train-test split
5. **Model Building**

   * Implement **Decision Tree Classifier** using `scikit-learn`
   * Train the model on training data
6. **Model Evaluation**

   * Accuracy Score
   * Confusion Matrix
   * Classification Report
   * Visualize Decision Tree
7. **Insights & Results**

   * Interpret classification performance
   * Understand decision rules

---

##  Results

* The **Decision Tree Classifier** predicts if a customer subscribes to a term deposit.
* Key evaluation metrics:

  * **Accuracy Score**
  * **Precision, Recall, F1-Score**
  * **Confusion Matrix**
* A **tree visualization** provides interpretability for business insights.

---

##  How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/prodigy-task3-decisiontree.git
   cd prodigy-task3-decisiontree
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Decision_tree.ipynb
   ```
3. Run all cells sequentially to reproduce results.

---

##  Internship Info

This project is submitted as **Task 3: Implement a Decision Tree Classifier** under the **Prodigy InfoTech Data Science Internship Program**.

---

##  Contact

For queries, collaborations, or feedback, feel free to connect with me:

* **LinkedIn:** [gowthamgshivamuthy](https://www.linkedin.com/in/gowthamgshivamuthy)
* **Gmail:** [gowthamgshivamuthy@gmail.com](mailto:gowthamgshivamuthy@gmail.com)

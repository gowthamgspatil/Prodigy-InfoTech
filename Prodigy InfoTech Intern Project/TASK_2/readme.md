#  Task 2 – Titanic Survival Prediction (EDA)

This project is created as part of **Prodigy InfoTech Internship – Task 2**.
The task involves performing **Exploratory Data Analysis (EDA)** on the Titanic dataset to identify patterns and insights that influenced survival during the Titanic disaster.

---

##  Project Structure

```
├── train.csv                       # Training dataset (with survival labels)
├── test.csv                        # Test dataset (without survival labels)
├── gender_submission.csv           # Sample submission file
├── Exploratory Data Analysis.ipynb # Jupyter Notebook with analysis & visualizations
└── README.md                       # Project documentation
```

---

##  Dataset Description

The dataset is provided by **Kaggle – Titanic: Machine Learning from Disaster**.

* **train.csv** → Passenger data with survival information (`Survived`).
* **test.csv** → Passenger data without survival labels.
* **gender\_submission.csv** → Example submission format.

**Important Features:**

* `Survived` → Target (0 = Did not survive, 1 = Survived)
* `Pclass` → Passenger Class (1 = 1st, 2 = 2nd, 3 = 3rd)
* `Sex` → Gender
* `Age` → Passenger age
* `SibSp` → Siblings/Spouses aboard
* `Parch` → Parents/Children aboard
* `Fare` → Ticket fare
* `Embarked` → Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

---

##  Steps Performed (EDA)

1. **Data Cleaning**

   * Handled missing values in `Age`, `Cabin`, and `Embarked`.
   * Converted categorical variables into readable form.

2. **Data Exploration & Visualization**

   * Plotted distributions of Age, Sex, Pclass, and Fare.
   * Analyzed survival rates by gender, class, and age groups.
   * Used heatmaps and bar charts to show correlations.

3. **Key Insights**

   * Women had a much higher survival rate than men.
   * 1st class passengers had better survival chances than 2nd & 3rd.
   * Younger passengers (especially children) had higher survival chances.

---

##  Example Visualizations

*  Survival rate by **Gender**
*  Survival rate by **Passenger Class**
*  Age distribution of survivors vs non-survivors
*  Correlation heatmap of features

---

##  Installation

Clone this repository and install dependencies:

```bash
git clone https://github.com/your-username/prodigy-task2-titanic.git
cd prodigy-task2-titanic
pip install -r requirements.txt
```

---

##  Usage

Run the Jupyter Notebook to reproduce the analysis:

```bash
jupyter notebook "Exploratory Data Analysis.ipynb"
```

---

##  Results

* Women and children were prioritized in rescue efforts.
* Passenger class played a major role in survival.
* Fare and embarkation point also showed patterns linked to survival.

---

##  Contact

* **LinkedIn**: [gowthamgshivamurthy](https://www.linkedin.com/in/gowthamgshivamuthy)
* **Gmail**: [gowthamgshivamurthy@gmail.com](mailto:gowthamgshivamurthy@gmail.com)

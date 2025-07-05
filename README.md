# 🚢 Titanic Survival Prediction using Decision Trees

This project explores how decision trees can be used to predict passenger survival on the Titanic based on various features such as age, gender, ticket class, and more.

## 📊 Dataset

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- **Features used**:
  - `Pclass` (Ticket class)
  - `Sex`
  - `Age`
  - `SibSp` (Siblings/Spouses aboard)
  - `Parch` (Parents/Children aboard)
  - `Fare`
  - `Embarked`

## 🎯 Objective

To build a Decision Tree classifier that predicts whether a passenger survived based on their characteristics.

## 🛠️ Tools & Libraries

- Python (Jupyter Notebook)
- `pandas`, `numpy` for data preprocessing
- `seaborn`, `matplotlib` for data visualization
- `scikit-learn` for machine learning and evaluation

## 📈 Workflow

1. **Data Cleaning**  
   - Handled missing values (`Age`, `Embarked`)
   - Converted categorical variables into numerical
2. **Exploratory Data Analysis**  
   - Explored survival rates across features (e.g., gender, class)
3. **Model Training**  
   - Trained a `DecisionTreeClassifier` from `sklearn`
   - Tuned hyperparameters (e.g., `max_depth`)
4. **Evaluation**  
   - Used accuracy score, confusion matrix
   - Visualized decision tree structure
5. **Interpretation**  
   - Found important features affecting survival

## 🔍 Key Insight

> Females and passengers in 1st class had significantly higher survival rates, while males in 3rd class had the lowest.

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/okeyirobbinson/Decision-tree-project.git
   cd Decision-tree-project


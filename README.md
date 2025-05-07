
# 🚢 Titanic Survival Predictor

This project is a machine learning model that predicts the survival chances of passengers on the Titanic using the famous Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic). The objective is to apply data science and ML techniques to classify whether a passenger survived or not based on features like age, gender, passenger class, etc.

---

## 🧠 Project Goals

- Clean and preprocess real-world data  
- Perform exploratory data analysis (EDA)  
- Build and train ML classification models  
- Evaluate and compare performance  
- Predict survival outcome for new data

---

## 📁 Project Structure



├── data/
│   └── train.csv
├── notebooks/
│   └── Titanic\_Survival\_Predictor.ipynb
├── models/
│   └── model.pkl
├── README.md
└── requirements.txt



## 📊 Dataset Description

The dataset contains information on passengers such as:

- `Pclass`: Passenger class (1st, 2nd, 3rd)
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Fare`: Fare paid for the ticket
- `Embarked`: Port of embarkation
- `Survived`: Target variable (0 = No, 1 = Yes)

---

## 📌 Key Features

- Data preprocessing (handling missing values, encoding, scaling)
- Visual analysis (survival rates by gender, class, age groups)
- Classification using:
  - Logistic Regression
  - Random Forest
  - Decision Tree
  - Support Vector Machine (optional)
- Model evaluation (accuracy, confusion matrix, etc.)
- Saving trained model for reuse

---

## 🧰 Technologies Used

- Python 3.x  
- Jupyter Notebook  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn  
- Joblib / Pickle

---

## 🚀 Getting Started

1. Clone the repository

```bash
git clone https://github.com/Rayhan-Dodi/Titanic-Survival-Predictor.git
cd Titanic-Survival-Predictor
````

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the notebook

Open the notebook in Jupyter:

```bash
jupyter notebook notebooks/Titanic_Survival_Predictor.ipynb
```

---

## 🧪 Example Results

> Replace or update these once available

* Accuracy: \~85% on validation data
* Feature importance graph
* Confusion matrix

---

## ✅ Status

✅ Complete for educational/demo purposes. Could be extended with more models or a web interface (e.g., Flask/Streamlit) in the future.

---

## ✍️ Author

* **Name**: Rayhan Kabir Dodi
* **GitHub**: [@Rayhan-Dodi](https://github.com/Rayhan-Dodi)

---

## 📄 License

Licensed under the **MIT License** – use freely with attribution.

---

## 🙌 Acknowledgments

* [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
* Scikit-learn documentation
* Online ML learning resources

---

```



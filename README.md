 # Predicting Diabetes Onset 🩺💡

## Project Overview
This project focuses on predicting the onset of diabetes using various machine learning models. The goal is to develop a predictive model based on health-related features to determine the likelihood of diabetes.

## Dataset
The dataset includes the following features:
- **Pregnancies**: Number of pregnancies  🤰
- **Glucose**: Plasma glucose concentration (2 hours in an oral glucose tolerance test)  🩸
- **BloodPressure**: Diastolic blood pressure (mm Hg)  💉
- **SkinThickness**: Triceps skin fold thickness (mm)  📏
- **Insulin**: 2-Hour serum insulin (mu U/ml)  🧪
- **BMI**: Body mass index (weight in kg/(height in m)^2) ⚖️
- **DiabetesPedigreeFunction**: A measure of likelihood of diabetes based on family history
- **Age**: Age of the individual (years)  🎂
- **Outcome**: Whether the individual has diabetes (1) or not (0) ✅❌

## Models Used
- **GaussianNB**
- **DecisionTreeClassifier**
- **RandomForestClassifier**
- **LogisticRegression**
- **AdaBoostClassifier**
- **XGBClassifier**
- **SVC**
- **GradientBoostingClassifier**
- **Neural Network**

## Installation
To run this project, you need to install the following Python libraries:
- pandas  📜
- numpy  🧮
- scikit-learn  🛠️
- xgboost  🚀
- tensorflow (for Neural Networks) 🧠

You can install them using pip:
```bash
pip install pandas numpy scikit-learn xgboost tensorflow
```

## Usage
Clone the repository:
```bash
git clone https://github.com/chandkund/Predicting-Diabetes-Onset
```
## Navigate to the project directory:
```bash
cd Predicting-Diabetes-Onset
```
## Run the main script:
```bash
python main.py
```
Results
The project evaluates the performance of various models on the dataset, providing insights into which model performs best for predicting diabetes onset.

License
This project is licensed under the MIT License - see the [LICENSE](LICENSE)file for details.

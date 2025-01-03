# Insurance Claim Prediction Project

### Overview
This project uses machine learning to predict insurance claim amounts based on customer attributes. It analyzes factors like age, BMI, smoking status, and region to estimate insurance charges.

## Data Description
The dataset (insurance.csv) contains the following features:

+ age: Age of the insurance policyholder
+ sex: Gender of the policyholder
+ bmi: Body Mass Index
+ children: Number of dependents
+ smoker: Smoking status (yes/no)
+ region: Geographic region
+ charges: Insurance charges (target variable)

## Project Structure
insurance-claim-prediction_version2.ipynb: Main Jupyter notebook containing:
+ Data preprocessing
+ Exploratory data analysis with visualizations
+ Feature engineering
+ Model training and evaluation
+ Predictive analysis

## Key Findings
+ Smokers tend to have significantly higher insurance charges
+ Age shows a positive correlation with insurance charges
+ Number of children impacts insurance costs
+ Region has minimal impact on charges

## Model Performance
Using Random Forest Regressor:

+ MSE: 29,586,927.57
+ RMSE: 5,439.38
+ R² Score: 0.808

## Dependencies
+ Python 3.x
+ NumPy
+ Pandas
+ Matplotlib
+ Seaborn
+ Scikit-learn
## Run Locally

Clone the repository

```bash
  git clone https://github.com/NoWon1/insurance-claim-prediction_version.git
```

Go to the project directory

```bash
  cd insurance-claim-prediction_version
```

Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

Start the server

```bash
jupyter notebook insurance-claim-prediction_version2.ipynb
```


## Screenshots

![seaborn.axisgrid.PairGrid at 0x2a1399f62a0](insurance-claim-prediction_version/Output SSs/output1.png?raw=true "PairGrid ")
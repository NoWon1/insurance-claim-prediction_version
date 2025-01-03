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

![output15](https://github.com/user-attachments/assets/7dfb05fc-3b57-47d8-bf6e-141bb7898341)
![output14](https://github.com/user-attachments/assets/b47376aa-b867-418a-8d3b-3fba06218d3f)
![output13](https://github.com/user-attachments/assets/eef467f5-f7e9-4e5a-b93a-d096dc98952d)
![output12](https://github.com/user-attachments/assets/08faed64-7964-4e44-9a8d-d9f582591d2d)
![output11](https://github.com/user-attachments/assets/b17cca4d-44ed-47e9-ac0d-556e5a36ba24)
![output10](https://github.com/user-attachments/assets/cce6aba1-b0d9-46df-bd59-3b3dc2648194)
![output9](https://github.com/user-attachments/assets/9e92adf4-4526-4a23-a30a-dff179ae24ee)
![output8](https://github.com/user-attachments/assets/4228b015-e445-4435-97f9-43fec570639a)
![output7](https://github.com/user-attachments/assets/76b2fb25-99c2-4e09-a5b3-5caae2685884)
![output6](https://github.com/user-attachments/assets/6d1de54b-716f-4bfc-b722-256416228c4f)
![output5](https://github.com/user-attachments/assets/c1cbd23b-d798-4dc8-8862-0e4542375507)
![output4](https://github.com/user-attachments/assets/09f20d1d-36be-4256-9ab9-3da0951b1927)
![output3](https://github.com/user-attachments/assets/26c312e6-ea64-43b5-af2a-12a4ecd1a9b5)
![output2](https://github.com/user-attachments/assets/714b53e1-e91d-4bd8-9c77-64a328086df8)
![output1](https://github.com/user-attachments/assets/f18593e5-c906-434b-9fa7-3ec4156acc3b)

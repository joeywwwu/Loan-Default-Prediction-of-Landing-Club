# Loan Default Prediction of Landing Club

## About:
In this project, I analyze the Lending Club data to predict whether the borrowers will repay their loan to better manage the risk of loan service. Lending Club is an American person-to-person loan company, headquartered in San Francisco, California. I chose to analyze the data of Lending Club because it is the world's largest person-to-person (p2p) lending platform, which has a credible dataset with a huge amount of digital footprints.

The main problem I focus on is to decide whether I should lend money to my potential clients. I built Logistic Regression, Random Forest, Neural Network, and SVM models to predict whether a client was "fully paid" or "charged off" the loan in the year of 2018. Since borrowers who default cause the most losses to the lender, if I could identify these borrowers with models, I can reduce the losses to the lender.

## Methods:
### 1. Data Collection
We gathered data from Kaggle, ensuring a comprehensive dataset for analysis.

### 2. Data Cleaning and Wrangling
Ensured data was prepped for exploratory analysis and machine learning model

### 3. Exploratory Data Analysis (EDA)
Conducted data visualization of key parameters, and performed filtering and representation of data to understand data distributions and relationships.

### 4. Supervised Machine Learning - Classification
Performed predictive analysis using classification models. Standardized data were split into train/test sets and fit using several types of classification models. Best parameters were chosen using grid search techniques before assessing model accuracy for the best-fit model from each type.

### 5. Model Evaluation
Implemented cross-validation to ensure model robustness. Evaluated model performance using metrics such as accuracy, recall, precision, and ROC-AUC scores.

## Results
- Implemented and evaluated multiple models including Logistic Regression, Random Forest, KNN, and SVM to predict target outcomes.
- Tuned models using 5-fold cross-validation, achieving ~91% out-of-sample recall, ~98% test accuracy, and ~96% AUC scores


## Report
The final report can be found [here](https://github.com/joeywwwu/Loan-Default-Prediction-of-Landing-Club/blob/main/results/Final%20Report.pdf).

## Repository Structure
- `notebooks/`: Includes Jupyter notebooks with detailed analysis and modeling steps.
- `results/`: Contains final report and final results.
- `README.md`: This file.
- `requirements.txt`: Dependencies required to install

## Instructions
To replicate this project, follow these steps:
1. Clone the repository.
2. Ensure all dependencies are installed (see `requirements.txt`).
3. Run the provided Jupyter notebooks to follow the analysis and modeling steps.
4. Review the results and visualizations for insights.


# Salary Prediction - Machine Learning Project

#### 🧑‍🏫 Author: [Amrita Neogi](https://www.linkedin.com/in/amritaneogi/)

![image](https://github.com/AmritaNeogi/Data-Science-Project-Salary-Prediction/blob/af8ee38e243d6ce9133a4c2594e3a94f44482db0/Salary%20Prediction.jpg)

This project aims to create a model to predict the salary based on the years of experience.

## Getting Started
### Prerequisites
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, sklearn

### Installation
- Clone the repository
```
git clone https://github.com/username/project.git
```
- Install required libraries
```
pip install pandas numpy matplotlib seaborn sklearn
```

## Usage
Run the following command in the terminal to execute the project:
```
python main.py
```

## Overview of the Code

1. **Correlation Matrix** to understand the relationship between the two variables: YearsExperience and Salary
2. **Split the dataset** in to train(YearsExperience) and test(Salary) data. 
3. **Data Modelling** with Simple Linear Regression.
4. **Model Optimazation** using Gradient Descent.
5. **Hyperparameter Tuning** with GrridSearch() to find the best model.
6. **Normalization** with StandardScaler() and performing Gradient Descent on it again.
7. Performing Hyperparameter tuning on the normalized data and fitted it on the best model.
8. Performed **Convergence of Gradient Descent** to find if model has found optimal values for the coefficients.

## References
- Kaggle Dataset: [Salary_dataset]( https://www.kaggle.com/code/lakyierealice/simple-linear-regression/input?scriptVersionId=120332371&select=Salary_dataset.csv)

## License
This project is licensed under the GNU GENERAL PUBLIC License.
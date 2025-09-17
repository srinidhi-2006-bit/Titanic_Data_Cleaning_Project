# Titanic_Data_Cleaning_Project

## Overview
```
This project demonstrates the process of cleaning and preprocessing the Titanic dataset.
The main goal is to prepare the dataset for analysis or machine learning tasks by handling missing values,
encoding categorical variables, and standardizing numeric features.
```
## Folder Structure
```
Titanic_Data_Cleaning_Project/
├── data/ # Raw dataset
│ └── train.csv
├── cleaned/ # Cleaned dataset output
│ └── titanic_cleaned.csv
├─ titanic_data_cleaning.ipynb
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```

## Steps Performed
```
1. Import the libraries
2. Load the Dataset
3. Inspect the Dataset
4. Handle Missing Values
5. Encode categorical variables (`Sex`, `Embarked`)
6. Normalize numeric features (`Age`, `Fare`) using StandardScaler
7. Save the cleaned dataset into the `cleaned/` folder
```
## Output
```
- Cleaned CSV: `cleaned/titanic_cleaned.csv`
```
## Tools & Libraries
```
- Python
- Pandas
- NumPy
- scikit-learn
- Jupyter Notebook
```
## Conclusion
```
The Titanic dataset has been successfully cleaned and transformed into a consistent format.
It is now ready for further analysis and predictive modeling.
```

# 🚢 Titanic Data Analysis

This project explores the Titanic dataset using Python. I clean the data, create new features, and visualize survival patterns to uncover insights about the passengers.

---

## 📌 Step 1: Import Libraries
I start by importing the main libraries:
1. pandas → for data manipulation and analysis.  
2. numpy → for mathematical operations.  
3. matplotlib & seaborn → for creating visualizations.  

I also set some style preferences to make the plots easier to read.

---

## 📌 Step 2: Load Dataset & Overview
I load the Titanic dataset and check its structure:
1. Display the shape (rows × columns).  
2. Show the first few rows to preview the data.  
3. Use .info() to check column types and missing values.  
4. Apply .describe() to view summary statistics.  

---

## 📌 Step 3: Missing Values & Duplicates
I examine data quality issues:
1. Count missing values per column.  
2. Detect duplicates using .duplicated().  
3. This helps identify which columns need cleaning.  

---

## 📌 Step 4: Data Cleaning & Feature Engineering
I clean the dataset and create new features:
1. Fill missing Embarked with the most frequent value.  
2. Fill missing Fare (if any) with the median.  
3. Extract passenger Title (Mr, Mrs, Miss, etc.) from the Name.  
4. Group rare titles under a single category "Rare".  
5. Fill missing Age values using the median age per title.  
6. Create a binary feature HasCabin (1 if cabin known, else 0).  
7. Create FamilySize from SibSp + Parch + 1.  
8. Confirm no missing values remain (except Cabin itself).  

---

## 📌 Step 5: Visualizations
I plotted several graphs to explore survival patterns:
1. Survival rate by Pclass → passengers in 1st class had much higher survival.  
2. Survival by Sex → females had far higher survival than males.  
3. Age distribution → compared survivors and non-survivors by age.  
4. Survival by FamilySize → small families had higher survival chances.  
5. Correlation heatmap → checked numeric correlations.  
6. Survival by Title → titles like *Mrs* and *Miss* had higher survival rates than *Mr*.  

---

## 📌 Step 6: Question & Answer
I explored survival rates by both class and gender:
1. Created a pivot table of survival by Pclass and Sex.  
2. Ranked the groups from highest to lowest survival.  
3. Found that 1st class females had the highest survival rate (~97%).  

---

## 📂 Files
- titanic.csv → Dataset.  
- notebook.ipynb → Main analysis notebook.  
- README.md → Project description (this file).  

---

## 📊 Tools Used
- Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn)  
- Jupyter/Google Colab for analysis to Southampton (S) and Queenstown (Q).

# 🛳️ Titanic Dataset Analysis

This project is an **Exploratory Data Analysis (EDA)** of the famous Titanic dataset from [Kaggle](https://www.kaggle.com/competitions/titanic/data).  
The aim of the project is to explore the dataset, clean it, create visualizations, and answer interesting research questions.

## 📂 Project Structure
- `titanic.csv` → The dataset used for the analysis.  
- `titanic_analysis.ipynb` → Google Colab notebook with all steps: loading, cleaning, visualization, and insights.  
- `README.md` → Project description and instructions.  

## ⚙️ Requirements
This project is written in Python.  
It can be run in **Google Colab** or **Jupyter Notebook**.  

Install the required libraries with:

```bash
pip install pandas numpy matplotlib seaborn
🔎 Steps of Analysis
1. Explore the Dataset
Load the Titanic dataset.

Print the columns, data types, and check missing values.

Generate summary statistics for both numerical and categorical features.

2. Data Cleaning
Fill missing values (Age, Fare, Embarked).

Handle duplicate rows (if any).

Extract useful features (e.g., Title from passenger names).

Create new features like FamilySize and HasCabin.

3. Visualizations
Survival rate by Class (Pclass).

Survival rate by Gender (Sex).

Age distribution of survivors vs. non-survivors.

Survival by Family Size.

Correlation heatmap of numerical variables.

Survival by Passenger Title.

4. Research Questions
I tried to answer the following interesting questions:

Which group (class + gender) had the highest survival rate?
→ Answer: Women in 1st class had the highest survival chance.

Which embarkation port had the highest survival rate (considering only ports with at least 50 passengers)?
→ Answer: Port C (Cherbourg) showed the highest survival rate among large groups.

📊 Example Visualization
Survival rate by passenger class:


(Tip: Save your plots from the notebook into a docs/ folder and link them here.)

🚀 How to Run
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/titanic-analysis.git
cd titanic-analysis
Open titanic_analysis.ipynb in Google Colab or Jupyter Notebook.

Upload the titanic.csv dataset to your environment.

Run the notebook step by step.

📌 Results & Insights
Women had a much higher survival rate than men.

First-class passengers had better survival chances compared to other classes.

Age and family size also played a role in survival.

Passengers from Cherbourg (C) had slightly better survival outcomes compared to Southampton (S) and Queenstown (Q).

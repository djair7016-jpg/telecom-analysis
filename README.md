# telecom-analysis
📌 Project Description
This project aims to analyze the behavior of ConnectaTel’s customers—a telecommunications company in Latin America—in order to understand how users actually use mobile services.
Through data analysis, the project seeks to:

Identify usage patterns.
Detect outliers.
Understand which customer segments have distinct needs.
Optimize the commercial offering.
Improve the user experience.

The analysis is conducted using data cleaning techniques, descriptive statistics, visualization, and customer segmentation.

📂 Datasets Used
plans.csv 
Catalog of mobile plans with information on:

Price
Included benefits
Features of each plan

users_latam.csv
User information:

Personal data
Plan subscribed to
Sign-up date
Churn status

usage.csv
Record of user activity:

Calls
Messages
Duration
Activity length

🛠️ Project Methodology
Step    Action    Business Outcome
1    Load and explore the plans, users_latam, and usage datasets    Understand the data structure and types
2    Identify quality issues    Detect nulls, sentinel values, and out-of-range dates
3    Basic data cleaning	Consistent data ready for analysis
4    Summary statistics    Identification of key metrics and typical behavior
5    Visualization and outlier detection    Identification of patterns, biases, and anomalies
6    Segmentation    Creation of actionable segments for business strategies
7    Executive insights    Development of conclusions and recommendations
8    Publication    Reproducible delivery via GitHub

🚀 How to run the project

### Option 1: Google Colab (Recommended)
1. **Open notebook**: 
https://colab.research.google.com/github/djair7016-jpg/telecom-analysis/blob/main/S7%20Version-Estudiante-Project-ConnectaTel.ipynb?hl=es#scrollTo=9fbb1a91
2. **Upload datasets**: The CSV files must be in the `/datasets/` folder in Colab
   - Upload `plans.csv`
   - Upload `users_latam.csv` 
   - Upload `usage.csv`

3. **Run**: Runtime > Run all (or run cell by cell)


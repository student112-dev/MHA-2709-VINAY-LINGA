Programming Solution – PDA CW2: NEPTUNE Loan Data Analysis
Project Overview
This programming solution was developed as part of PDA CW2 (Programming for Data Analysts) for the MSc Management with Data Analytics program. The aim was to programmatically extract, clean, and analyze two datasets (PDF and Excel) related to past loan applications for NEPTUNE Financial Services (NFS), with the goal of uncovering actionable insights and improving operational decision-making.

File Sources
NEPTUNE Loan Data.xlsx (maintained by the Sales Team)

NEPTUNE_Loans_Database_Table.pdf (extracted by the Database Administrator)
Code Libraries Used

Library	Purpose
pandas	DataFrame handling, cleaning, and manipulation
numpy	Numerical operations and handling of missing values
matplotlib	Visualizations (charts, bar plots, pie charts)
seaborn	Advanced and aesthetically pleasing statistical visualizations
tabula-py	Extracting tabular data from the PDF file
warnings	Suppressing unnecessary warnings for a cleaner notebook output
All libraries are well-documented, open-source, and widely used in the data science industry.
Language & Platform
Language: Python 3
Platform: Google Colab Notebook (.ipynb)

Python was chosen due to its widespread use in data analytics, strong community support, rich ecosystem of libraries (pandas, matplotlib, seaborn, tabula-py), and integration with cloud platforms like Google Colab which offers scalability and sharing features.
Code Design (with Pseudocode)
This solution was designed to be modular, interpretable, and code-agnostic, meaning it can easily be adapted to other programming languages if required.

1. Load PDF and Excel datasets into memory.
2. Normalize column names and data types.
3. Merge the two datasets on Loan_ID.
4. Clean the merged data:
    - Handle missing values
    - Remove duplicates
    - Decode numeric codes into categorical labels
5. Perform Exploratory Data Analysis (EDA):
    - Calculate totals, averages, distributions
    - Generate visual charts and summaries
6. Present findings with business insights.
This structure can easily be replicated in R, SQL, or Java-based analytics platforms.

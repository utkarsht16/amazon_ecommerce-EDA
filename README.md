# Amazon Ecommerce EDA

This project focuses on understanding Amazon retail data by cleaning the dataset, analyzing important trends, and generating meaningful insights. The analysis was done in Visual Studio Code using Python.


---

# Project Files

◦ analysis.ipynb        - Main notebook with all analysis

◦ amazon_dataset/       - Contain Raw dataset

◦ df_all_cleaned.csv    - Final cleaned dataset
    
◦ README.md             - Project documentation


---

# Project Summary

The dataset contained multiple CSV files that were merged and cleaned to create a single final dataset (df_all_cleaned.csv).
During the project, some code cells produced errors, but these were fixed or removed to maintain a clean and logical workflow.
Markdown cells were added throughout the notebook to explain each phase of the project clearly.


---

# Steps Performed in the Project

## 1. Imported and Loaded the Dataset

◦ Loaded all CSV files from the amazon_dataset folder.

◦ Checked file shapes, columns, and data quality.


## 2. Merged All the Files

◦ Combined multiple files into one dataset.

◦ Ensured columns aligned properly.

◦ Verified the final row count.


## 3. Data Cleaning

◦ Performed several cleaning steps, including:

◦ Removing empty or irrelevant rows

◦ Dropping duplicates

◦ Fixing data types

◦ Handling formatting issues

◦ Renaming unclear column names

◦ Removing corrupted or unreadable rows

◦ Created the final cleaned file:
   df_all_cleaned.csv

## 4. Exploratory Data Analysis (EDA)

- Analyzed various patterns such as:

   ◦ Top-selling products

   ◦ Sales by category

   ◦ Price patterns

   ◦ Rating distribution

   ◦ Customer behavior indicators

- Visualizations were created to support each finding.

## 5. Markdown Documentation

◦ Added markdown cells throughout the notebook to explain:

◦ What each section does

◦ Key insights from the results

◦ Important functions

◦ Why certain cleaning or transformations were necessary

◦ This makes the notebook readable and professional.

## 6. Error Handling

◦ During development:

◦ Some code cells generated errors

◦ Incorrect code was removed

◦ Only clean, working code remains

◦ Comments were added to explain logic


## 7. Git & GitHub

◦ Created a new repository

◦ Committed all files

◦ Pushed project to GitHub




---

# Key Insights From the Project

◦ Sales vary significantly across product categories

◦ Some products dominate revenue despite low order count

◦ Ratings show clear patterns in customer satisfaction

◦ Price differences heavily impact sales volume

◦ Seasonal trends were observed in certain categories


---

# Technologies Used

◦ Python

◦ Pandas

◦ NumPy

◦ Matplotlib

◦ Seaborn

◦ Visual Studio Code

◦ Git & GitHub



---

 # How to Run This Notebook

1. Clone the repository


2. Install the required libraries


3. Open analysis.ipynb in Jupyter Notebook/Visual Studio Code


4. Run the cells in order


---

# Results & Final Thoughts

This project successfully combined multiple Amazon product datasets into a single, unified dataset. After cleaning, handling missing values, removing duplicates, and fixing inconsistencies, the final dataset became structured and ready for analysis.
Through EDA, several useful insights were discovered about pricing patterns, real vs. fake prices, review counts, and movie-related metadata.

All work—including data cleaning, merging, and EDA—was performed inside VS Code using a .ipynb notebook, making the workflow easy to understand and reproducible.
Overall, the project achieved its goal of practicing a real-world data analysis pipeline.

---

# Author

Utkarsh Tyagi

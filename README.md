
# Zomato Data Cleaning Project

## 📌 Description
This Jupyter Notebook project cleans and preprocesses the **Zomato restaurant dataset** step by step.  
It covers basic data cleaning operations such as dropping irrelevant columns, renaming columns, handling missing values, cleaning numeric fields, and exporting the cleaned data.

## ✅ Tasks Performed
- Load the raw `zomato.csv` file.
- Drop unnecessary columns (`url`, `phone`, `reviews_list`, etc.).
- Rename columns for clarity (e.g., `approx_cost(for two people)` → `two_people_cost`).
- Remove rows with missing critical data (like `location`, `cuisines`, `two_people_cost`).
- Clean `two_people_cost` by removing commas and converting to integer.
- Calculate cost per person.
- Clean `rating` by handling 'NEW' or '-' and filling missing values with mean.
- Export the cleaned data to `Zomato_Clean_Data.csv`.

## 📂 Files Included
- **Zomato_Cleaning_StepByStep_Notebook.ipynb** — Jupyter Notebook with each cleaning step in a separate cell.
- **Zomato_Clean_Data.csv** — Cleaned output file (created after running the notebook).

## ⚙️ Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- numpy

## 🚀 How to Run
1. Place `zomato.csv` in your working directory.
2. Open the notebook in Jupyter and run each cell in order.
3. The cleaned CSV will be saved as `Zomato_Clean_Data.csv`.

## 👨‍💻 Author
This mini project demonstrates basic data cleaning in Python using **pandas** and **numpy**.

Happy Learning! 📊✨

#  Data Aggregation & Grouping

This project demonstrates data manipulation and summarization using **Pandas**.  
It covers operations such as **Merge**, **Join**, **GroupBy**, and **Aggregation** to extract meaningful insights from structured data.

---

##  Features
- Split data into training and testing sets.  
- Merge multiple DataFrames based on common columns.  
- Group data to calculate averages and counts.  
- Aggregate data and measure score ranges.  
- Export the final summarized dataset to a CSV file.

---

##  Project Structure
```

data-aggregation-grouping/
│
├── Data_Aggregation_Grouping.ipynb     # Main notebook (code and outputs)
├── Students_Grouped_Data.csv           # Final grouped dataset
├── README.md                           # Project documentation
└── .gitignore                          # Ignored files and system configs

````

---

##  Requirements
```bash
pip install pandas
````

---

##  How to Run

1. Open the notebook in **Google Colab** or **Jupyter Notebook**.
2. Run all cells sequentially.
3. Review the merged, grouped, and aggregated results.
4. The final output will be saved as `Students_Grouped_Data.csv`.

---

##  Key Operations

* **Merge** → Combine two or more DataFrames.
* **GroupBy** → Summarize data by categories (e.g., gender).
* **Aggregation** → Calculate averages, counts, and ranges.
* **Export** → Save the final summarized data to CSV.

---

##  Example Output

| StudentGender | MathScore | StudentCount | ScoreRange |
| ------------- | --------- | ------------ | ---------- |
| female        | 88        | 2            | 4          |
| male          | 75        | 2            | 5          |

---

##  Author

**Osama Suliman**
Data Science Student — Umm Al-Qura University
[GitHub: os7i](https://github.com/os7i)



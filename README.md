# IMDb Movie Data Analysis (Python Project)

This project analyzes the top 100 IMDb-rated movies from the past decade
using Python and Pandas. The goal is to extract meaningful insights related
to movie profitability, ratings, actor popularity, and audience voting patterns.

---

## Dataset Description
The dataset contains information about:
- Movie titles
- IMDb ratings
- MetaCritic scores
- Gross and budget values
- Actor Facebook likes
- Audience votes (CVotesU18)

---

## Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Tasks Performed

### 🔹 Task 1: Data Loading & Inspection
- Read CSV file using `read_csv`
- Checked rows and columns
- Inspected column data types
- Generated statistical summaries

### Task 2: Data Analysis
- Converted budget and gross values to million dollars
- Calculated movie profit
- Identified top 10 profitable movies
- Found loss-making movies
- Scaled MetaCritic scores to match IMDb scale
- Calculated average ratings
- Filtered highly-rated movies with low MetaCritic scores
- Identified top 5 actor trios by Facebook popularity
- Extracted top 10 movies based on youth votes (CVotesU18)

---

## Key Insights
- Profitability does not always correlate with high ratings
- Some movies have strong IMDb ratings despite low MetaCritic scores
- Actor popularity significantly impacts movie visibility
- Youth votes highlight different preferences compared to critics

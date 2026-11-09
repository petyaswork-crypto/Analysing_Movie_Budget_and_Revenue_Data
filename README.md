# 🎥 Analysing_Movie_Budget_and_Revenue_Data

Welcome to my notebook! 
In these pages I do a data analysis of a movie dataset, examining how production budget relates to worldwide gross revenue — and how that relationship has changed across decades.


## About 

These pages contain an exercise in data cleaning, exploratory analysis, and simple linear regression. Starting from a "dirty" CSV with currency-formatted strings and mixed types, it walks through cleaning, filtering, visualization, and modelling to answer a concrete question: does spending more on a film actually earn more at the box office?
Stay tuned to find what the answer is!


## Key findings

- Budget predicts revenue — but only for modern films. The R² of 0.56 for new films vs. 0.03 for old films is the headline result.

- Production budgets have risen sharply since the 1970s, visible in the release-date scatter plot.

- Over a third of films (37.28%) lose money relative to their worldwide gross.

- Not all $0 revenue means failure — some of these films simply hadn't come out yet when the data was collected.


## How to Run

### Prerequisites

- Python 3.8+
- pandas, numpy, matplotlib, seaborn

### Steps
1. Copy the repository
2. Place "cost_revenue_data.csv" in the same repository as the notebook
3. Open the file "Movie Budget and Revenue Data analysis.ipynb" in Google Colab or Visual Studio Code (these are optional, you can use any tool you preffer).
4. Run all cells top to bottom


## What This Project Demonstrates

- Data cleaning discipline — handling currency strings, type coercion, and invalid rows before analysis

- Defensive analysis — verifying assumptions (e.g., checking whether $0 revenue means "no revenue" or "not yet released") rather than trusting the raw data

- Iterative exploration — using filtering, grouping, and visualization to build understanding before modelling

- Modelling with judgment — fitting separate models per era rather than one global model


## Credits

This analysis is built as part of the "100 Days of Code – The Complete Python Pro Bootcamp" (Udemy), then extended and commented for portfolio use.


## 💬 P.S Thank you for reading! If you found this useful or have thoughts on how it could be improved, I'd love to hear from you.


# 📈 Page View Time Series Visualizer

This project is part of the [freeCodeCamp Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/) certification.  
It uses forum page view data from freeCodeCamp to generate visualizations and identify trends and patterns over time.

---

## 📁 Project Structure

```
time_series_visualizer.py   # Script containing the plotting logic  
main.py                     # Development entrypoint to test your function  
test_module.py              # Unit tests for validation  
fcc-forum-pageviews.csv     # Forum page view dataset  
line_plot.png               # Output line plot  
bar_plot.png                # Output bar plot  
box_plot.png                # Output box plots  
```

---

## 📊 Features

- Loads page view data from May 2016 to December 2019  
- Cleans the dataset by removing the top and bottom 2.5% of data  
- Generates:
  - A **line plot** of daily page views  
  - A **bar plot** showing average monthly page views per year  
  - A **box plot** showing year-wise and month-wise distributions  
- Adds proper titles, labels, and legends

---

## 🧪 Technologies Used

- **Python 3**
- **Pandas**
- **Matplotlib**
- **Seaborn**

---

## 🚀 How to Run the Project

1. Install the required libraries:

```bash
pip install pandas matplotlib seaborn
```

2. Run the project:

```bash
python main.py
```

What it does:

- Generates the following plot files:  
  - `line_plot.png`  
  - `bar_plot.png`  
  - `box_plot.png`  
- Runs unit tests from `test_module.py`

---

## 📈 Output Plot Descriptions

- **Line Plot (`line_plot.png`)**  
  Daily page views over time with a clear upward or downward trend.

- **Bar Plot (`bar_plot.png`)**  
  Displays the average monthly page views grouped by year.  
  X-axis: Year — Y-axis: Average Page Views  
  Legend: Months (January to December)

- **Box Plots (`box_plot.png`)**  
  Two side-by-side plots:
  - **Year-wise box plot** showing the trend across years
  - **Month-wise box plot** showing seasonal patterns  
  X-axis: Year/Month — Y-axis: Page Views

---

## 📚 Dataset Source

> Forum page view statistics collected from freeCodeCamp between 2016 and 2019.

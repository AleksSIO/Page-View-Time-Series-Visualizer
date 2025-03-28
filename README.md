# 📈 Page View Time Series Visualizer

This project is part of the **freeCodeCamp Data Analysis with Python** certification.  
It involves cleaning and visualizing time series data of page views on the freeCodeCamp forum.

## 🗃️ Dataset

The dataset used (`fcc-forum-pageviews.csv`) contains daily page view counts from **May 2016 to December 2019**.

Each row includes:
- `date`: the day of the measurement
- `value`: number of page views on that day

## 📊 Visualizations

### 1. Line Plot
Displays page views over time to identify trends and fluctuations.

**File**: `line_plot.png`  
**Function**: `draw_line_plot()`

---

### 2. Bar Plot
Shows the **average monthly page views** grouped by **year**.

**File**: `bar_plot.png`  
**Function**: `draw_bar_plot()`  
- X-axis: Years  
- Y-axis: Average Page Views  
- Legend: Months (January to December)

---

### 3. Box Plot
Displays distribution of page views by **year** and by **month**.

**File**: `box_plot.png`  
**Function**: `draw_box_plot()`  
- Left: Year-wise box plot (Trend)
- Right: Month-wise box plot (Seasonality)

---

## 🧹 Data Cleaning

To remove outliers and clean the dataset:
- Removed the **top 2.5%** and **bottom 2.5%** of the data based on page views.

## 🛠️ How to Run

```bash
python3 main.py

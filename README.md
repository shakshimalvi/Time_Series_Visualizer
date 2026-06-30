# Time Series Visualizer

This project is part of the **freeCodeCamp Data Analysis with Python Certification**.

The project analyzes time series data from the freeCodeCamp.org forum to identify trends, seasonality, and growth in daily page views using **Pandas**, **Matplotlib**, and **Seaborn**.

---

## Project Overview

The dataset contains the daily number of page views on the freeCodeCamp.org forum from **May 9, 2016** to **December 3, 2019**.

The data is cleaned by removing the top 2.5% and bottom 2.5% of page view values to eliminate outliers. Three different visualizations are then created to better understand long-term trends and seasonal patterns.

---

## Features

* Import and clean time series data using Pandas
* Remove outliers using percentile filtering
* Create a line chart to visualize daily page views
* Create a grouped bar chart showing average monthly page views by year
* Create year-wise and month-wise box plots to analyze trends and seasonality

---

## Technologies Used

* Python 3
* Pandas
* Matplotlib
* Seaborn

---

## Dataset

**File:** `fcc-forum-pageviews.csv`

**Columns:**

* `date` – Date of the observation
* `value` – Number of page views

---

## Project Structure

```text
time-series-visualizer/
│
├── fcc-forum-pageviews.csv
├── time_series_visualizer.py
├── main.py
├── test_module.py
├── README.md
├── line_plot.png
├── bar_plot.png
└── box_plot.png
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/time-series-visualizer.git
```

Move into the project directory:

```bash
cd time-series-visualizer
```

Install the required libraries:

```bash
pip install pandas matplotlib seaborn
```

---

## Running the Project

Execute:

```bash
python main.py
```

The program generates the following files:

* `line_plot.png`
* `bar_plot.png`
* `box_plot.png`

---

## Visualizations

### 1. Line Plot

Displays the daily number of forum page views over time, highlighting the overall growth trend.

### 2. Bar Plot

Shows the average daily page views for each month, grouped by year, making yearly comparisons easy.

### 3. Box Plots

* **Year-wise Box Plot:** Illustrates yearly trends and distribution of page views.
* **Month-wise Box Plot:** Highlights seasonal variations across different months.

---

## Data Cleaning

Outliers are removed by excluding:

* The lowest 2.5% of page view values
* The highest 2.5% of page view values

This ensures the visualizations focus on typical user activity.

---

## Skills Demonstrated

* Data Cleaning
* Time Series Analysis
* Data Visualization
* Exploratory Data Analysis (EDA)
* Pandas Data Manipulation
* Matplotlib Visualization
* Seaborn Statistical Graphics

---

## Certification

This project was completed as part of the **freeCodeCamp Data Analysis with Python Certification**.

---

## License

This project is intended for educational purposes as part of the freeCodeCamp curriculum.

# working-with-plotly
# 📊 Plotly Data Visualization Project

## 📌 Overview
This project demonstrates the creation of interactive and exportable data visualizations using the Plotly library in Python. Various chart types are implemented to analyze and present data clearly and professionally.

All visualizations are saved as high-resolution image files suitable for reports, presentations, and portfolio use.

---

## 📂 Project Structure

```
project/
│
├── working_with_plotly.ipynb
│
├── images/
│   ├── income_vs_age.png
│   ├── economic_survey.png
│   ├── bicycle_sales_line_plot.png
│   ├── bicycle_sales.png
│   ├── pass_percentage_classes.png
│   ├── crime_statistics_bubble_chart.png
│   ├── household_expenditure_pie_chart.png
│   ├── family_chart_sunburst.png
│
└── README.md
```

---

## 🛠 Technologies Used

- Python
- Plotly
- Plotly Express
- NumPy
- Kaleido (for saving images)
- Jupyter Notebook

---

## 📈 Visualizations Created

### 1. Scatter Plot
**File:** `income_vs_age.png`

- Shows relationship between age and income
- Helps identify income distribution across age groups

---

### 2. Scatter Plot with Titles
**File:** `economic_survey.png`

- Improved scatter plot with axis labels and title
- Represents economic survey data clearly

---

### 3. Line Plot
**File:** `bicycle_sales_line_plot.png`

- Shows monthly bicycle sales trend
- Useful for identifying growth and decline periods

---

### 4. Bar Chart
**File:** `pass_percentage_classes.png`

- Displays pass percentage across different classes
- Helps compare performance between grades

---

### 5. Histogram
**File:** `height_distribution_histogram.png`

- Shows distribution of heights
- Helps understand frequency distribution

---

### 6. Bubble Chart
**File:** `crime_statistics_bubble_chart.png`

- Displays crime statistics by city
- Bubble size represents number of crimes

---

### 7. Pie Chart
**File:** `household_expenditure_pie_chart.png`

- Shows household spending distribution
- Useful for budget analysis

---

### 8. Sunburst Chart
**File:** `family_chart_sunburst.png`

- Shows hierarchical family structure
- Demonstrates hierarchical data visualization

---

## 💾 Saving Charts as Images

Charts are saved using Kaleido:

```python
fig.write_image("filename.png", width=1200, height=800, scale=2)
```

---

## ⚙ Installation

Install required libraries:

```bash
pip install plotly numpy kaleido notebook
```

---

## ▶ How to Run

1. Open terminal
2. Navigate to project folder
3. Run:

```bash
jupyter notebook
```

4. Open:

```
working_with_plotly.ipynb
```

5. Run all cells

---

## 📊 Skills Demonstrated

- Data visualization
- Plotly chart creation
- Exporting charts as images
- Data analysis visualization techniques
- Professional reporting visuals

---

## 📚 Applications

These visualizations are useful for:

- Data Analysis
- Business Reports
- Dashboard Development
- Portfolio Projects
- Academic Projects

---

## 👩‍💻 Author

Aswini

---

## ⭐ Key Learning Outcome

This project demonstrates complete mastery of Plotly visualization including:

- Scatter plots
- Line charts
- Bar charts
- Histograms
- Bubble charts
- Pie charts
- Sunburst charts
- Saving visualizations as high-quality images

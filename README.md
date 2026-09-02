# Food Delivery Business Performance Visualization

## Project Overview

This project presents a complete **Data Visualization Portfolio** for analyzing a Food Delivery Business Performance dataset using **Python, Matplotlib, and Seaborn**.

The objective is to explore business performance and identify meaningful patterns related to orders, revenue, cities, cuisines, marketing expenditure, delivery operations, customer ratings, weather conditions, and order channels.

The project follows a structured visualization workflow, with every visualization accompanied by an interpretation of the insight it reveals.

---

## Objectives

The major objectives of this project are to:

* Analyze changes in orders and revenue over time.
* Compare business performance across different cities.
* Identify high-performing and low-performing cuisines.
* Investigate the relationship between marketing spend and revenue.
* Examine the relationship between delivery time and customer ratings.
* Understand the impact of weather conditions on business performance.
* Compare different order channels.
* Analyze distributions and identify potential outliers.
* Study correlations between important business variables.
* Communicate insights using appropriate data visualizations.

---

## Dataset

The project uses the **Food Delivery Business Performance Dataset**.

### Dataset Features

| Feature                   | Description                          |
| ------------------------- | ------------------------------------ |
| `Order_Batch_ID`          | Unique identifier for an order batch |
| `Date`                    | Date of the order batch              |
| `Month`                   | Month of the order                   |
| `Day`                     | Day of the week                      |
| `City`                    | City where the order was placed      |
| `Cuisine`                 | Cuisine category                     |
| `Order_Channel`           | Platform/channel used for ordering   |
| `Weather`                 | Weather condition                    |
| `Orders`                  | Number of orders                     |
| `Average_Order_Value`     | Average value of an order            |
| `Revenue`                 | Revenue generated                    |
| `Marketing_Spend`         | Marketing expenditure                |
| `Discounts`               | Discounts offered                    |
| `Avg_Delivery_Minutes`    | Average delivery time                |
| `Customer_Rating`         | Customer rating                      |
| `Repeat_Customer_Percent` | Percentage of repeat customers       |

---

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook / Google Colab**

---

## Visualizations Included

The notebook contains a comprehensive collection of visualizations:

### 1. Line Plots

* Daily orders over time
* Monthly revenue trend
* Monthly orders and revenue comparison

### 2. Bar Charts

* Revenue by city
* Orders by city
* Revenue by cuisine
* Average order value by cuisine
* Revenue by order channel
* Average revenue by weather

### 3. Scatter Plots

* Marketing spend vs revenue
* Delivery time vs customer rating

Regression lines are included to make the overall relationship easier to interpret.

### 4. Histograms

* Distribution of orders
* Distribution of revenue
* Distribution of customer ratings

### 5. Box Plots

* Revenue distribution by city
* Delivery time by weather
* Customer ratings by order channel

### 6. Violin Plot

* Customer rating distribution by weather

### 7. Count Plots

* Order channel distribution
* Weather condition distribution

### 8. Heatmaps

* City vs cuisine revenue heatmap
* Correlation heatmap of numerical business variables

---

## Key Analysis Areas

The project focuses on answering questions such as:

* How do order volumes change over time?
* Which months generate the highest revenue?
* Which cities contribute the most revenue?
* Which cuisines are the most profitable?
* Is higher marketing spending associated with higher revenue?
* Does delivery time have a relationship with customer satisfaction?
* Which weather conditions are associated with better business performance?
* Which order channel generates the most revenue?
* Which variables have strong relationships with revenue?
* Are there unusual observations or potential outliers?

---

## Data Preparation

Before visualization, the dataset is prepared using Pandas.

The preprocessing includes:

* Converting the `Date` column into datetime format.
* Converting numerical variables into appropriate numeric data types.
* Checking for missing values.
* Checking and removing duplicate records.
* Creating useful time-based variables.
* Organizing months chronologically.
* Preparing aggregated datasets for visualization.

---

## Insights and Interpretations

Each visualization in the notebook is followed by a brief interpretation explaining the pattern observed in the chart.

The analysis focuses not only on creating charts but also on understanding **what the charts communicate about business performance**.

Examples of insights explored include:

* Revenue differences between cities.
* Performance differences between cuisines.
* Relationship between promotional investment and revenue.
* Potential relationship between delivery efficiency and customer satisfaction.
* Performance differences under various weather conditions.
* Revenue contribution from different ordering platforms.

---

## Project Structure

```text
Food-Delivery-Business-Performance-Visualization/
│
├── Day14_Food_Delivery_Visualization_Dataset.csv
│
├── Food_Delivery_Business_Performance_Visualization.ipynb
│
├── README.md
│
├── requirements.txt
│
└── .gitignore
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Food-Delivery-Business-Performance-Visualization.git
```

### 2. Navigate to the Project Directory

```bash
cd Food-Delivery-Business-Performance-Visualization
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Notebook

Using Jupyter:

```bash
jupyter notebook
```

Or open the `.ipynb` file directly in **VS Code**.

The notebook can also be uploaded to **Google Colab**.

---

## Requirements

The project requires the following Python libraries:

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## Business Value

This visualization portfolio demonstrates how data visualization can transform raw business data into actionable insights.

The analysis can help food delivery businesses understand:

* Customer demand patterns
* High-performing markets
* Popular and profitable cuisines
* Marketing effectiveness
* Delivery performance
* Customer satisfaction
* Channel performance
* Weather-related operational patterns

These insights can support better decisions regarding **marketing, operations, customer experience, and business expansion**.

---

## Important Note

Correlation observed in the analysis represents an **association between variables and does not necessarily imply causation**.

Business decisions should therefore consider additional factors and domain knowledge before drawing causal conclusions.

---

## Author

**Pratyush Sharma**

B.Tech Computer Science & Engineering
Artificial Intelligence & Machine Learning

---

## Project Highlights

* Complete visualization workflow
* Multiple Matplotlib and Seaborn visualization techniques
* Business-focused exploratory analysis
* Interpretation after every major visualization
* Correlation and relationship analysis
* Clean and reproducible Jupyter/Colab notebook
* GitHub-ready project structure

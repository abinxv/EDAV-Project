# Sleep Quality Analysis 

## Overview

This project analyzes how lifestyle factors such as **physical activity, diet, age, and daily habits** affect sleep quality.
Using Python libraries like **Pandas, NumPy, Matplotlib, and Seaborn**, we explore patterns in a dataset containing information about individuals' sleep behavior and health-related activities.

The goal of this project is to **identify the factors that contribute to better sleep quality** and visualize these relationships through data analysis.

---

## Dataset Description

The dataset contains information about individuals' **sleep habits, physical activity, and health indicators**.

### Columns in the Dataset

| Column                      | Description                                              |
| --------------------------- | -------------------------------------------------------- |
| **User ID**                 | Unique identification number for each individual         |
| **Age**                     | Age of the individual                                    |
| **Gender**                  | Gender of the individual (`f` = female, `m` = male)      |
| **Sleep Quality**           | Sleep quality score from **1–10** (10 = best sleep)      |
| **Bedtime**                 | Time the individual goes to sleep (24-hour format)       |
| **Wake-up Time**            | Time the individual wakes up (24-hour format)            |
| **Daily Steps**             | Number of steps taken per day                            |
| **Calories Burned**         | Total calories burned per day                            |
| **Physical Activity Level** | Activity level (`low`, `medium`, `high`)                 |
| **Dietary Habits**          | Diet category (`healthy`, `medium`, `unhealthy`)         |
| **Sleep Disorders**         | Whether the individual has sleep disorders (`yes`, `no`) |
| **Medication Usage**        | Whether sleep medication is used (`yes`, `no`)           |


---

## Technologies Used

The analysis was performed using the following Python libraries:

* **Python**
* **Pandas** – Data manipulation and cleaning
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization

---

## Project Workflow

### Data Loading

* Imported dataset using **Pandas**
* Inspected data using `.head()`, `.info()`, and `.describe()`

### Data Cleaning

* Checked for missing values
* Converted time columns if necessary
* Standardized categorical variables

### Exploratory Data Analysis (EDA)

Visualizations were created to analyze relationships between variables:

Examples:

* Sleep Quality vs Physical Activity Level
* Sleep Quality vs Dietary Habits
* Sleep Quality vs Age
* Impact of Sleep Disorders on Sleep Quality
* Correlation heatmaps for numerical features

### Visualization

Using **Matplotlib and Seaborn**, various plots were created:

* Bar plots
* Box plots
* Histograms
* Correlation heatmaps
* Scatter plots

These visualizations help reveal trends affecting sleep quality.

---

## Key Findings

From the analysis:

✔ Individuals with **high physical activity levels** tend to have better sleep quality.
✔ **Healthy dietary habits** are associated with improved sleep scores.
✔ **Sleep disorders significantly reduce sleep quality.**
✔ Individuals taking **sleep medication often report lower natural sleep quality.**
✔ Consistent sleep schedules (bedtime & wake-up time) correlate with better sleep.

---

## Example Visualizations

Some of the visualizations generated in the project include:

* Distribution of Sleep Quality
* Sleep Quality by Activity Level
* Sleep Quality by Diet Type
* Correlation Heatmap of Numerical Variables

---

## Conclusion

This project demonstrates how **data analysis and visualization can help uncover patterns in lifestyle habits affecting sleep quality**. Even with synthetic data, the analysis provides insights into how **exercise, diet, and health conditions may influence sleep health.**

---


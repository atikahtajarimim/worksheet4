# Week 4 Worksheet Repository: Exploratory Data Analysis

This repository is the starter repository for the week 4 exploratory data analysis activity.

## Repository Structure

- `README.md`: this file
- `requirements.txt`: Python packages for the activity
- `data/clean/store_week_clean.csv`: cleaned sample data for the activity
- `code/worksheet4_eda_student.ipynb`: notebook to complete
- `output/`: save any figures or exported outputs here

## Analysis Notes

### What files are in the repository?
The repository contains the cleaned store dataset, the student analysis notebook, and an output folder with 6 exported PNG figures.

### What does the dataset appear to describe?
The dataset describes weekly performance metrics for retail stores, specifically tracking labor hours, wages, and sales revenue across four geographic regions.

### Which variables did you examine first?
I examined `weekly_sales`, `total_hours`, and `avg_hourly_pay` to understand the basic distributions and ranges of the numeric data.

### What distributional patterns stood out?
- `total_hours` and `avg_hourly_pay` show significant "heaping" at round numbers, indicating standardized staffing blocks.
- `weekly_sales` follows a right-skewed distribution.

### What did the scatter plots and correlations suggest?
The scatter plots showed a strong positive linear relationship between hours and sales (Pearson = 0.75). Pay also has a moderate positive correlation with sales (0.41).

### What changed when you adjusted the scale or plotted by group?
- **Scale:** Using a log scale on the y-axis (Sales) made it easier to compare the relationship across the full range of store sizes.
- **Group:** Plotting by `staffing_model` revealed three distinct clusters, showing that the model type (Heavy vs. Standard vs. Light) is the main driver of performance.



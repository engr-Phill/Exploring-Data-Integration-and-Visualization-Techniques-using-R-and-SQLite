# Exploring-Data-Integration-and-Visualization-Techniques-using-R-and-SQLite

## Overview
This project demonstrates data manipulation, SQLite database creation, and data analysis using R. It includes importing data, creating SQLite tables, querying data, and performing exploratory data analysis and visualization tasks.

## Files
- `movies500.csv`: Contains movie data.
- `movies500_genres.csv`: Contains movie genres data.
- `genres.csv`: Contains genre names.

## Setup
Ensure you have R and the required packages (`RSQLite`, `dplyr`, `tidyr`, `ggplot2`) installed.

## Instructions
1. **Data Import and Database Setup**
   - Read CSV files into R.
   - Create an SQLite database `movies.sqlite`.
   - Copy data into SQLite tables.

2. **Data Queries**
   - Count rows in `movies`.
   - Output movies with runtime greater than 480 minutes.
   - Find movies with "love" in the title.
   - Create and modify a `genres` table.

3. **Motor Vehicle Analysis**
   - Read and process `motor_vehicle_modified.csv`.
   - Filter vehicles by transmission type and make.
   - Perform data transformations and create contingency tables.

4. **Star Wars Dataset Analysis**
   - Analyze the Star Wars dataset.
   - Visualize species distribution and relationships between height and mass.
   - Identify and handle outliers in the data.

5. **Visualization**
   - Generate various plots: bar charts, scatter plots, boxplots.
   - Visualize relationships and distributions within datasets.

## Libraries Used
- `RSQLite`: For SQLite database operations.
- `dplyr`, `tidyr`: For data manipulation and transformation.
- `ggplot2`: For data visualization.




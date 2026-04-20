Netflix EDA Project
📌 Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Titles dataset to understand content distribution, trends, and patterns in Netflix movies and TV shows.

The analysis is done using Python (Pandas + Matplotlib) in a Jupyter Notebook.

📊 What This Project Does

In this project, I:

Loaded and explored the Netflix dataset (8807 titles)
Cleaned missing values in key columns
Analyzed Movies vs TV Shows distribution
Studied content ratings (TV-MA, PG, R, etc.)
Found top countries producing Netflix content
Identified most common genres
Analyzed release year trends
Studied movie duration distribution
Visualized insights using graphs

👉 In short: This project explores Netflix data to understand what content is available and how it is distributed.

📁 Files in This Project
File	Description
netflix_titles.csv	Dataset (8807 rows, 12 columns)
Netflix_EDA_Basic.ipynb	Main Jupyter Notebook containing EDA
📊 Dataset Columns
Column	Description
show_id	Unique ID of each title
type	Movie or TV Show
title	Name of content
director	Director name
cast	Actors involved
country	Production country
date_added	Date added to Netflix
release_year	Year of release
rating	Content rating (TV-MA, PG, etc.)
duration	Duration (minutes / seasons)
listed_in	Genre
description	Short summary
⚙️ Requirements

Install required libraries:

pip install pandas matplotlib jupyter
🚀 How to Run
Download the project folder
Open terminal in the folder
Start Jupyter Notebook:
jupyter notebook Netflix_EDA_Basic.ipynb
Run all cells step-by-step
📈 Analysis Performed
1. Data Loading
Loaded dataset using Pandas
Checked shape, info, and missing values
2. Data Cleaning
Handled missing values using fillna() and dropna()
3. Content Type Analysis
Compared Movies vs TV Shows using graphs
4. Rating Analysis
Found most common content ratings
5. Release Year Trends
Analyzed how content changed over time
6. Country Analysis
Identified top countries producing Netflix content
7. Genre Analysis
Found most popular genres
8. Duration Analysis
Studied movie duration distribution
📌 Key Insights
Netflix has ~8800 titles
Movies are more than TV Shows (~70% vs ~30%)
Most content is rated TV-MA
Content increased significantly after 2015
USA produces the highest number of titles
Most common genre is Drama
Average movie duration is around 100 minutes
🎯 Skills Used
Python (Pandas)
Data Cleaning
Exploratory Data Analysis (EDA)
Data Visualization (Matplotlib)
Insight generation from real-world dataset
⭐ Conclusion

This project is a beginner-friendly EDA analysis of Netflix data, helping to understand content trends and strengthen data analysis skills for ML/Data Science roles.

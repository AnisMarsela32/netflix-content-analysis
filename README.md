# Netflix Content Trends (2008 - 2021) 📺

This project explores and visualizes trends in Netflix content from 2008 to 2021 using Python (Pandas, Seaborn, Matplotlib) and Tableau.

## Project Overview

Netflix is one of the largest streaming platforms in the world. This analysis dives into the type of content (Movies or TV Shows), their genres, countries of origin, and trends in the number of titles added over the years.

## 🗂 Dataset

- **Source**: [Netflix Titles on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- ~8,800 rows with attributes like:
  - `type`, `title`, `country`, `release_year`, `date_added`, `duration`, `listed_in` (genres)

## Objectives

- Understand the distribution of Movies vs TV Shows
- Discover popular genres and content origins
- Explore content trends over time
- Create a visual dashboard (Tableau)

## Visualizations

- Pie chart: Distribution of Movies vs TV Shows
- Bar chart: Top 10 Genres
- Bar chart: Top 10 Producing Countries
- Histogram: Content released over the years
- Stacked bar chart: Content added by year (by type)

## Tools Used

- Python (Pandas, Seaborn, Matplotlib)
- Tableau Public
- Jupyter Notebook

## Tableau Dashboard

🔗 [Click here to view the dashboard on Tableau Public](https://public.tableau.com/app/profile/anis.marsela2969/viz/Netflix_17484912331770/NetflixContentTrends20082021?publish=yes)

## Data Cleaning

Missing values handled in:
- `director`, `cast`, `country`, `date_added`, `duration`
New columns:
- `duration_num`, `duration_unit`, `year_added`

## Project Structure


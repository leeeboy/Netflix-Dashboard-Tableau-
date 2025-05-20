# 📊 Netflix Dashboard (Tableau)

This project is an interactive Tableau dashboard I built to analyze the Netflix dataset (6,000+ titles). The goal was to create a user-friendly interface that allows exploration of Netflix content based on various filters and visualizations.

## 🔧 Features

* **Dropdown Filter**: Select between **Movie** or **TV Show**, then choose a specific **title**. The dashboard dynamically displays:

  * Rating
  * Description
  * Release Date
  * Listed Date
  * Duration
  * Genre

* **World Map**: Visualizes the geographic distribution of content based on the country where the movie or show was listed.

* **Content Distribution**: Shows count and percentage split between Movies and TV Shows.

* **Rating Distribution**: Histogram displaying the spread of ratings across all titles.

* **Top 10 Genres**: Bar chart showcasing the most common genres in the dataset.

* **Area Plot**: Compares the number of Movies vs. TV Shows over time.

## 🧹 Data Cleaning & Preparation

Before visualizing, I spent time cleaning and preparing the dataset:

* Handled missing values (e.g., missing countries, dates)
* Standardized date fields (Release Date, Listed Date)
* Normalized and split multi-genre and multi-country entries
* Filtered out irrelevant or incomplete rows

This step was crucial for making sure the dashboard was accurate and responsive to user interaction.

## 📈 Tools Used

* Tableau (for visualization and dashboarding)
* Excel / Google Sheets (for initial data preprocessing)

## 📂 Dataset

The dataset was sourced from [Netflix Titles on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows). It contains information such as title, director, cast, country, release year, rating, duration, and more.

## ✅ How to Use

1. Open the Tableau dashboard (link or `.twbx` file if hosted)
2. Use the dropdown menus to explore specific types or titles
3. Hover over charts for additional insights
4. Click to filter and interact with the visualizations

## 🚀 Future Improvements

* Add more granular filters (e.g., by director, cast)
* Integrate Tableau Public to allow full online interactivity
* Use Tableau Prep or Python (Pandas) for more scalable data cleaning

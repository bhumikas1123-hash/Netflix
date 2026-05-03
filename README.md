# Netflix Exploratory Data Analysis (EDA)

## Project Overview

This project presents an in-depth **Exploratory Data Analysis (EDA)** of the Netflix dataset. The analysis focuses on understanding content distribution, trends, and patterns across movies and TV shows available on Netflix.

The dataset includes attributes such as title, type, genre, cast, country, release year, rating, and duration, enabling comprehensive analysis of Netflix’s content library.

---

## Objectives

* Understand dataset structure and features
* Perform data cleaning and preprocessing
* Analyze distribution of Movies vs TV Shows
* Study year-wise content trends
* Explore rating patterns and audience targeting
* Perform country-wise and genre analysis
* Generate meaningful insights using data visualization

---

## Dataset Information

* **Source**: Kaggle
* **Rows**: 7,787
* **Columns**: 12 (reduced after cleaning)
* Includes both **categorical and numerical data**

---

## Tools & Technologies Used

* Python 
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Cleaning & Preparation

* Handled missing values using:

  * Filling (director → “Unknown”, country → mode)
  * Dropping (date_added, rating with minimal nulls)
* Removed unnecessary columns (show_id, description)
* Standardized formats (date_added, duration)
* Treated inconsistent data (multiple countries, mixed duration formats)

---

## Key Analysis Performed

### 1. Content Distribution

* Movies ≈ 70%
* TV Shows ≈ 30%

### 2. Year-wise Trends

* Rapid growth after 2014
* Peak around 2019–2020
* Slight decline in 2021

### 3. Country-wise Analysis

* USA dominates content production
* India is the second-largest contributor
* Other countries have significantly lower representation

### 4. Rating Analysis

* TV-MA is the most common rating
* Followed by TV-14 and TV-PG
* Focus on adult and teenage audiences

### 5. Duration Analysis

* Movies mostly between 80–120 minutes
* TV Shows usually have 1–2 seasons
* Longer series are rare

### 6. Genre Analysis

* Drama is the most dominant genre
* Comedy and Documentaries follow
* Horror and niche genres have limited presence

---

## Key Insights

* Netflix content is **movie-dominated**
* Strong focus on **mature audience content**
* Content growth peaked before COVID-19
* Significant **geographical imbalance (USA-heavy)**
* Preference for **shorter, engaging content**

---

## Conclusion

This project highlights how data analysis can uncover patterns in digital content platforms. It provides insights into Netflix’s content strategy, audience targeting, and global distribution trends.

---

## References

* Kaggle Dataset: [https://www.kaggle.com/datasets/imtkaggleteam/netflix](https://www.kaggle.com/datasets/imtkaggleteam/netflix)
* Additional Notebook: [https://www.kaggle.com/code/davinci00/netflix-explortory-project](https://www.kaggle.com/code/davinci00/netflix-explortory-project)

---

## Acknowledgment

This project was completed as part of my learning journey in **Data Analytics and Business Intelligence**.

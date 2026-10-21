# marathon_usa

# 🏃 Marathon USA — Exploratory Data Analysis Using Python

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of ultra-marathon running events in the USA using Python. The objective is to analyze race performance, explore athlete demographics, and identify patterns in running speed across different race distances, age groups, genders, and seasons.

The project involves data cleaning, preprocessing, filtering, feature engineering, and visualization to transform raw marathon data into meaningful insights.

## 🎯 Project Objectives

- Analyze athlete performance across different race distances.
- Compare average running speeds between male and female athletes.
- Explore the relationship between athlete age and average speed.
- Identify age groups with strong performance in 50-mile races.
- Examine seasonal variations in running performance.
- Understand patterns and distributions in marathon participation and performance.

## 📂 Dataset

**Dataset:** [The Big Dataset of Ultra-Marathon Running — Kaggle](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running)

The dataset contains information about ultra-marathon events and participating athletes.

Key columns include:

- `Year of event` — Year in which the event took place.
- `Event dates` — Date of the race.
- `Event name` — Name and location of the event.
- `Event distance/length` — Race distance, such as 50km or 50mi.
- `Event number of finishers` — Number of athletes finishing the event.
- `Athlete performance` — Recorded race completion time.
- `Athlete country` — Athlete's country code.
- `Athlete year of birth` — Athlete's birth year.
- `Athlete gender` — Gender of the athlete.
- `Athlete age category` — Athlete's age classification.
- `Athlete average speed` — Average running speed recorded for the athlete.

## 🛠️ Tools & Technologies

- **Python** — Data analysis and manipulation
- **Pandas** — Data cleaning, filtering, grouping, and aggregation
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook / Google Colab** — Interactive analysis

## 🔍 Project Workflow

### 1. Data Collection
- Downloaded the ultra-marathon dataset using KaggleHub.
- Loaded the dataset into Pandas DataFrames for analysis.

### 2. Data Cleaning and Preprocessing
- Inspected dataset structure, column names, and data types.
- Handled missing values in the selected analysis dataset.
- Converted event dates into datetime format.
- Standardized and transformed relevant columns.
- Extracted useful information from event names and race distances.

### 3. Data Filtering and Feature Engineering
- Filtered events based on location and race distance.
- Focused on 50km and 50-mile races for performance comparisons.
- Created analytical features such as race length, athlete age, and season.
- Prepared the data for grouped analysis and visualization.

### 4. Exploratory Data Analysis
- Examined race-distance distributions.
- Compared athlete performance by gender and race length.
- Analyzed average speed distributions for 50km and 50-mile events.
- Investigated the relationship between age and running speed.
- Compared average speeds across age groups.
- Explored seasonal differences in running performance.

### 5. Data Visualization
Used Matplotlib and Seaborn to create visualizations, including:

- Histograms for race-distance distributions.
- Distribution plots for average running speed.
- Violin plots to compare speed distributions by gender.
- Regression plots to explore age and speed relationships.

## 📊 Key Business Questions

This analysis explores the following questions:

1. How does average running speed vary between 50km and 50-mile races?
2. How do male and female athletes compare in average running speed?
3. What is the relationship between athlete age and running performance?
4. Which age groups demonstrate higher average speeds in 50-mile races, subject to a minimum participation threshold?
5. Does average running speed vary across seasons?
6. How are athletes distributed across different race distances?

## 💡 Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Data filtering using Pandas
- Feature engineering
- Date and time manipulation
- GroupBy and aggregation
- Statistical data visualization
- Comparative performance analysis
- Extracting insights from large datasets

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/nitingwl25-source/marathon_usa.git
   ```

2. Navigate to the project directory:

   ```bash
   cd marathon_usa
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn kagglehub
   ```

4. Open `marathon.ipynb` in Jupyter Notebook or Google Colab.

5. Run the notebook cells sequentially.

**Note:** The notebook downloads the dataset through KaggleHub. Ensure that the dataset is accessible and that your environment has an internet connection.

## 👤 Author

**Nitin Agarwal**

Data Analyst | Python | SQL | Power BI | Data Visualization

- GitHub: [nitingwl25-source](https://github.com/nitingwl25-source)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/nitinagarwal25/)

---

If you find this project useful, feel free to ⭐ the repository!

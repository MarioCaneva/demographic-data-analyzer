# Demographic Data Analyzer

This Python project uses **Pandas** to analyze demographic data extracted from the **1994 U.S. Census database**. It answers a variety of questions about education, income, work hours, nationality, and occupation based on a given dataset.

## 📊 Key Analyses
- Race count breakdown
- Average age of men
- Percentage of people with a Bachelor's degree
- Income comparison between those with and without advanced education
- Work hour extremes and associated income
- Country with the highest proportion of high earners
- Most common high-paying occupation in India

## 🧮 Example Questions Answered
- What percentage of people with a Doctorate make more than 50K?
- Who works the fewest hours per week and still earns >50K?
- What is the most common occupation for wealthy people in India?

## 🗂️ Dataset
The dataset used is the **`adult.data.csv`** file, which must be placed in the project directory.

```bash
📁 your-repo/
├── adult.data.csv
└── demographic_data_analyzer.py
🧠 How It Works
python
Copy
Edit
from demographic_data_analyzer import calculate_demographic_data

calculate_demographic_data()
Example Output:
plaintext
Copy
Edit
Number of each race:
 White                 27816
Black                  3124
Asian-Pac-Islander     1039
Amer-Indian-Eskimo      311
Other                   271
...
📦 Requirements
Python 3

Pandas

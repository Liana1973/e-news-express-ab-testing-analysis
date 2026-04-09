# e-news-express-ab-testing-analysis
A/B testing and statistical analysis project for evaluating landing page performance and conversion behavior.
# E-News Express A/B Testing Analysis

## Project Overview
This project analyzes the effectiveness of a new landing page design for E-News Express, an online news platform.

The goal of the analysis is to determine whether the new landing page improves user engagement and conversion compared to the existing landing page.

This project applies exploratory data analysis and statistical hypothesis testing to support business decision-making.

---

## Business Objective
E-News Express wants to increase subscriptions by improving the design and relevance of its landing page.

The company conducted an A/B test to compare user behavior on the old and new landing pages.

---

## Dataset
The dataset contains information about user interactions with the two landing page versions.

### Variables:
- **user_id** – Unique user identifier
- **group** – Control or treatment group
- **landing_page** – Old or new landing page
- **time_spent_on_the_page** – Time spent on the page (in minutes)
- **converted** – Whether the user subscribed or not
- **language_preferred** – User’s preferred language

---

## Key Questions Answered
1. Do users spend more time on the new landing page than on the old landing page?
2. Is the conversion rate higher for the new landing page?
3. Does conversion depend on preferred language?
4. Is time spent on the new page the same across language groups?

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

---

## Methods Used
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Hypothesis Testing
- Two-sample independent t-test
- Two-sample proportions z-test
- Chi-square test of independence
- One-way ANOVA

---

## Key Business Value
This project demonstrates how statistical analysis can be used to evaluate product changes, user engagement, and conversion performance in a business setting.

---

## Files Included
- `E_News_Express_Project.ipynb` – Jupyter notebook
- `E_News_Express_Project.html` – Exported notebook version
- `abtest.csv` – Dataset used for analysis

---

## Author
Portfolio project completed as part of a business statistics and data analytics learning path.

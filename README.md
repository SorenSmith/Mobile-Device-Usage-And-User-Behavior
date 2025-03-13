# 📱 Mobile Device Usage and User Behavior

## 📚 About Data

This dataset offers a detailed analysis of mobile device usage patterns and user behavior classification. It includes 700 user data samples with metrics such as app usage time, screen-on time, battery consumption, and data usage. Each record is classified into one of five user behavior categories, ranging from light to extreme usage, enabling comprehensive analysis and modeling.

This dataset contains a csv table with 700 records, one for each user.

[Link](https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset)

## 💡 Highlights

- Valuations in year 2021 makes up one-third of total valuations since the beginning of time.
- Unicorns in United States and China outperformed the rest of the world with 72% overall valuations.
- Bytedance, SpaceX, SHEIN and Stripe are the most successful unicorns which performed better than an average unicorn at $71 billion.
- Unicorns in AI, E-Commerce, Fintech and Edtech industries are valued higher than the average unicorn at $3.5 billion. 
- A unicorn takes an average of 7 years to attain valuation of $1billion and become a unicorn.

## ✏️ Data Wrangling

Conducted simple data wrangling and data cleaning:
- Removed rows with missing values
- Cleaned `Valuation` and `Funding` columns and cast as float
- Exclude rows with "Unknown" `Funding` values
- Explode `Select Investors` column into individual rows for categorical analysis

📍 Jupyter script: [Notebook](https://github.com/katiehuangx/Maven-Unicorn-Challenge/blob/main/Maven%20Unicorn%20Companies%20-%20Data%20Wrangling.ipynb)

📍 Clean Data: [unicorn_companies_clean.csv](https://github.com/katiehuangx/Maven-Unicorn-Challenge/blob/main/unicorn_companies_clean.csv)

## 📊 Visualization

Produced a 1-pager dashboard using Tableau.

Tableau: [Link](https://public.tableau.com/app/profile/katie.huang/viz/UnicornCompanies_16502745371460/Unicorns?publish=yes)

![Unicorns-2](https://user-images.githubusercontent.com/81607668/164443885-986bf154-9884-4312-b7cd-a1e128ee24b2.png)

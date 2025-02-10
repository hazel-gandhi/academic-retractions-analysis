# 📉 Retractions in Academic Studies

This project is an analysis of academic retractions since 2010 and uses the database maintained by Retraction Watch, a New York-based group documenting global retractions in academia.

## 📁 Repo Guide

- 📄 **retraction_watch.csv**: Main CSV I downloaded from the Retraction Watch database to do my analysis
- 📝 **retraction-watch.ipynb**: Main notebook with all my code    
- 📂 **analysis/**: A folder with filtered dataframes that I used to make charts  
- 📂 **images**: All my charts created in R in png format



## 🎯 Aim

-  I [read](https://www.nature.com/articles/d41586-023-03974-8) about how academic retractions were on the rise and was curious to find where they happened the most, and the reasons behind them too. That was the main goal of the project.
-  Learn how to analyze large CSVs.
-  Use R for data visualization.

## 🔍 Findings

- China has surpassed all countries massively in the number of retractions, leading to a **nationwide audit** of all retractions and the reasons behind them.
- Retractions have also risen because of **paper mills**, publications that produce low-quality studies to sell authorship to people who want to make their CVs look better.
- Some prominent names of publishers that I noticed in the retractions were **IEEE**, *Nature*, **American Medical Association**, and *Sage*.

## 🛠️ Data Collection and Analysis Process

-  I used the [**Retraction Watch**](https://retractionwatch.com/) database for my analysis. The database is **massive** and dates back to the **1800s**, containing retractions from almost all major countries.
-  **Pushed the CSV into pandas** to make analysis easier.
- Filtered the data to **begin from 2010** (I decided going back 15 years was enough).
-  Made a lot of **methodological choices**:
  - There were many **similar reasons** but listed differently. I made some decisions and grouped them together to improve my charts. For example:
    - All kinds of **errors** (in data collection, analysis, images, etc.) were categorized under **"errors"**.
    - Fabrication and falsification were **clubbed together**.
    - Plagiarism and **fake peer review** had their own categories because they are **serious enough** to warrant separate classifications.
    -I also took some help from [this](https://www.nature.com/articles/d41586-023-03974-8) Nature article to help me categorize the reasons better.

## 🚀 New Skills Acquired / Improved Approaches

- Learned how to **define functions** to make data sorting easier. Without them, I would have had to create **a lot** of pivot tables and perform extreme dataframe filtering.
- 🔍 Used **regex** to clean up the data (especially dates).

## 🔄 Things I Would Change

- Chart size and readability: I exported the charts from **R**, and they looked fine, but when I put them in **HTML**, the fonts became **too small and unreadable**.
- I would have liked to have the time to **interview 2 research integrity specialists** to make my write-up more substantial.


# COVID-19 Data Analysis & Visualization (w3resource Project Track)

A comprehensive data science practice project using Python to analyze, aggregate, and visualize global COVID-19 dataset milestones. This project follows the curated exercises and tasks provided by [w3resource's COVID-19 Project Track](https://www.w3resource.com/python-exercises/project/covid-19/index.php).

---

##  Project Overview

The primary goal of this repository is to practice data engineering, filtering, and statistical plotting using real-world public health data. The project works with chronological daily reports containing data metrics such as **Confirmed**, **Deaths**, **Recovered**, and **Active** cases.

### Core Objectives Met:
* **Exploratory Data Analysis (EDA):** Loading dataset baselines, managing missing inputs, and displaying structured metadata (`.info()`, `.isna()`).
* **Data Aggregation:** Grouping records regionally (`.groupby()`) to discover state-level patterns, isolate Chinese provinces, and track recovery rates.
* **Top-Tier Performance Filtering:** Extracting top 10 impacted global regions using clean Pandas aggregation workflows like `.nlargest()`.
* **Dynamic Time-Series Visualization:** Generating statistical line plots mapping active cases and tracking global case changes across granular daily timelines.

---

##  Tech Stack & Libraries

This project maps solutions across Python's core data analytics ecosystem:

* **Pandas:** For structural dataframe manipulation, conditional masks, and multi-variable grouping.
* **Plotly Express:** For crafting clean, advanced dark-themed interactive visualizations (e.g., global case tracks).
* **Matplotlib:** For rendering foundational, static localized linear charts (e.g., country-wise analysis where deaths exceed 150).
* **Kaleido:** Integrated behind the scenes to convert interactive javascript plots into solid version-control assets.

```bash
pip install pandas plotly matplotlib kaleido

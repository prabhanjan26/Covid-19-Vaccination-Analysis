📌 Project Overview

This project explores COVID-19 vaccination data using Pandas and Matplotlib.
The dataset country_vaccinations_by_manufacturer.csv contains information about vaccinations administered by different vaccine manufacturers across countries.

The goal is to gain meaningful insights into vaccination rollouts worldwide and specifically focus on the European Union (EU).

📂 Dataset

File name: country_vaccinations_by_manufacturer.csv

Key columns:

location → Country/region name (e.g., Germany, European Union)

date → Date of vaccination report

vaccine → Manufacturer name (Pfizer, Moderna, AstraZeneca, etc.)

total_vaccinations → Cumulative doses administered for that manufacturer & location

⚙️ Installation & Setup

Clone this repo or download the notebook.

Install dependencies:

pip install pandas matplotlib seaborn


Launch Jupyter Notebook:

jupyter notebook


Open Data_Analysis.ipynb.

📊 Analysis Objectives

The analysis is structured in progressive steps:

🔹 General Insights (Global)

Data Cleaning & Exploration

Check missing values, duplicates, and data types.

Explore number of entries per country.

Earliest & Latest Rollout

Which country/region started vaccinations earliest and latest?

Manufacturer Coverage

Which manufacturers are used in the most countries?

Top 3 most widely administered vaccines globally.

🔹 Focus on European Union

Since location = "European Union" aggregates all member states, we extract insights at this level:

Vaccination Timeline

Plot total vaccinations over time.

Identify peaks and plateau phases.

Manufacturer Market Share

Distribution of vaccines (Pfizer, Moderna, AstraZeneca, etc.) in EU.

Small contributors grouped into "Others" for readability.

Adoption Over Time

When did each manufacturer enter the EU rollout?

How their shares evolved (stacked area chart).

Peak Vaccination Days

Detect dates with maximum vaccination spikes.

Trend Comparison

Compare daily vaccinations vs. rolling averages for smooth trends.

📈 Visualizations

Bar Charts → Vaccine usage across countries/manufacturers

Pie Charts → Market share of vaccines (with "Others" category for small shares)

Line Plots → EU vaccination timeline (cumulative & daily)

Stacked Area Plot → Manufacturer share changes over time

🧾 Key Findings (so far)

Pfizer is the dominant vaccine in the EU.

AstraZeneca and Moderna make up significant but smaller shares.

Tiny contributors (Sinovac, Covaxin, etc.) are negligible → grouped as "Others".

EU rollout shows rapid early growth, followed by a slowdown.

🚀 Next Steps

Compare EU vs. top individual member states (Germany, France, Italy).

Correlate vaccine rollout speed with case trends (requires case data).

Extend analysis to regional comparisons (Western vs. Eastern EU).

📌 Tools & Libraries

Python 3.9+

Pandas → Data manipulation

Matplotlib / Seaborn → Visualization

Jupyter Notebook → Interactive analysis

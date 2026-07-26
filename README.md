Hong Kong Old Age Living Allowance (OALA) Trend and Policy Impact Analysis (2013–2024)

Project Title: How did two forces – population aging and policy reforms – actually change the number of people receiving OALA over the past decade?

This project analyzes the trends, policy impacts, and economic implications of Hong Kong’s Old Age Living Allowance (OALA) from 2013 to 2024, using public data and Python-based data analysis (Pandas, Matplotlib).

The study divides the period into three policy phases:

Phase	Years	Policy Features

Phase 1	2013–2017	Single-tier OALA (Normal rate only)

Phase 2	2018–2021	Two‑tier system: Normal + Higher OALA

Phase 3	2022–2024	Unified OALA (merger of Normal and Higher Old Age Living Allowance)

📁 Project Structure


├── Project/
│   ├── persons_receiving_oala_2013_to_2024.csv      # Raw data by gender
│   ├── Persons_of_Receiving_OALA.csv                # Raw data of allowances every year
│   ├── total_persons_receiving_oala_2013_to_2024.csv # Total recipients per year (calculated)
│   ├── population_of_elders_2013_to_2024.csv        # Elderly population raw data
│   ├── population.csv                               # Population every year
│   ├── total_elder_population_2013_to_2024.csv      # Total population aged 65+ (calculated)
│   └── OALA_history.csv                             # Historical allowance amounts and asset limits
├── Poject of OALA 2013-2024.ipynb                   # Main Jupyter Notebook
└── README.md

📊 Key Analyses and Visualizations
1. Recipient Numbers vs. Elderly Population Coverage
Dual‑axis line charts for each policy phase show:

The total number of OALA recipients.

The percentage of elderly population (aged 65+) receiving the allowance.

The coverage rate increased from ~37% in 2013 to ~43% in 2024.

2. Policy Phase Averages
Bar chart comparing average recipients across the three phases:

2013–2017: 433,765

2018–2021: 581,089 (↑34.0%)

2022–2024: 717,226 (↑23.4%)

3. Correlation between Recipients and Elderly Population
Scatter plot with a correlation coefficient of 0.994, confirming that demographic aging is the primary driver of OALA uptake.

4. Allowance Value vs. Inflation
Using 2014 as the base year (CPI = 100), cumulative increases of the allowance are compared to cumulative inflation.

The allowance grew by 83.6% from 2014 to 2024, while CPI rose only 21.5% – indicating significant real purchasing power improvement.

5. Historical Allowance Table
A comprehensive table lists all adjustments to monthly amounts and asset limits (single/couple) from 2012 to 2025.

📦 Dependencies

pandas

matplotlib

jupyter

Running the Notebook
Simply open Poject of OALA 2013-2024.ipynb in Jupyter and execute all cells. All charts and tables will be generated automatically.

Running the Notebook
Simply open Poject of OALA 2013-2024.ipynb in Jupyter and execute all cells. All charts and tables will be generated automatically.

📌 Data Sources
Population data: Hong Kong Census and Statistics Department (Table 110‑01001)

OALA statistics and policy details: Social Welfare Department (SWD) and LegCo documents (see references in notebook)

🔍 Key Findings
Population aging is the dominant factor – the extremely high correlation (0.994) shows that the increase in recipients is overwhelmingly driven by the growing elderly population.

Policy expansions significantly boosted coverage – the introduction of the Higher OALA and later unification broadened eligibility and increased average recipients by over 65% from Phase 1 to Phase 3.

Allowance kept pace with living costs – cumulative allowance growth far exceeded inflation, ensuring improved real welfare for recipients.

👥 Team Members & Contributions
This project was completed as part of a group assignment at Hong Kong Baptist University (HKBU).
1. Chen ZiLi, Lily
2. Chan YIn Ching

Individual Contributions & Percentage

Member 1: Chan Yin Ching
1. Designed and coded some visualizations (scatter graph and line plots) using seaborn
2. Wrote the AI Disclosure sections 
3. Edited the video recorded (Adding pictures and subtitles)
4. Performed data merging and exploratory data analysis 
5. Drafted the narrative explanations of the scatter graph and dual line plots in the Jupyter Notebook
Estimated contribution: 50%

Member 2: Chen ZiLI 
1. Collected the data of the asset limits and monthly allowance of the OALA and CPI changes each year
2. Performed data merging and exploratory data analysis 
3. Created and refined some visualizations ( bar chart and dual line chart)
4. Scripted of the promotional video 
5. Drafted the narrative explanations of the bar chart and dual line chart in the Jupyter Notebook
Estimated contribution: 50%

=====================AI Disclosure====================

AI tool used: Deepseek and Chat GPT
Specific purposes:
1. Adding codes for detials in the graphs(colors, frontsize, labels)
2. Suming up the total elderly population and recipents from extracting data in csv documents
3. Suggestion for work division
4. Summarize the history of monthly amount and asset limit for single and couple regarding Old Age Living Allowance into a table.
5. Debugging code

📬 Contact
For any questions or collaboration opportunities, please reach out:

Email: chenzili764@gmail.com

LinkedIn: linkedin.com/in/zilichen2007

📝 License
This project is for educational purpose. All rights reserved by the team.

Thank you for visiting our repository! 🙌



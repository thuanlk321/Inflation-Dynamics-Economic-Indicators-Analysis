# 📊 Economic Indicators' Effect on the Inflation Rate

This project analyzes the relationships between key **macroeconomic indicators** and the **inflation rate** using World Bank data (2010–2023). The notebook explores how unemployment, GDP growth, and real interest rates interact with inflation, focusing mainly on the **United States** and **Canada**.

---

## 📂 Project Overview

- An exploratory data analysis of macroeconomic indicators and inflation  
- Visual insights into inflation, unemployment, GDP growth, and real interest rates  
- Data cleaning and preparation steps for reliable analysis  
- Graphical summaries using `matplotlib` and `pandas`  
- Special focus on the COVID-19 period (2020–2021) and the post-pandemic inflation surge  

---

## 🧠 Key Observations

- Unemployment and inflation generally move in opposite directions (consistent with the Phillips Curve)
- GDP growth and inflation tend to move together during demand-driven periods
- Real interest rates remained low through most of the 2010s and only rose after the 2021–22 inflation surge
- The COVID-19 shock temporarily disrupted the usual relationships between these indicators

---

## 🛠️ Technologies & Features Used

- Python  
- Jupyter Notebook  
- Pandas  
- Matplotlib  
- Seaborn  
- Data cleaning with `pandas`  
- Time-series visualizations with `matplotlib.pyplot`  
- Filtering and subsetting data for country-specific analysis  
- Summary statistics and correlation insights  

---

## 📊 Sample Visualizations

### 1. Correlation of Unemployment Rate, GDP Growth with Inflation Rate of Canada (2010–2023)
![Canada Economic Indicators](thumbnails/Correlation%20of%20Economic%20Indicators%20with%20inflation%20Rate%20of%20Can.png)

Shows how inflation, unemployment, and GDP growth in Canada moved over time.  
Notable patterns include the sharp drop in GDP growth and rise in unemployment during 2020 (COVID-19), followed by the inflation spike in 2021–2022.

---

### 2. Correlation of Unemployment Rate, GDP Growth with Inflation Rate of USA (2010–2023)
![USA Economic Indicators](thumbnails/Correlation%20of%20Economic%20Indicators%20with%20inflation%20Rate%20of%20USA.png)

Illustrates the relationships among the same indicators for the United States.  
The chart clearly shows the inverse movement between unemployment and inflation outside the pandemic period, as well as the strong rebound in growth and inflation after 2020.

---

🚀 How to Run
1. Clone the repository
Bashgit clone https://github.com/your-username/Inflation-Analysis.git
cd Inflation-Analysis

2. Install required libraries
Bashpip install pandas numpy matplotlib seaborn jupyter

3. Open the notebook
Bashjupyter notebook Inflation_Analysis.ipynb


📈 Main Conclusions

Unemployment and inflation generally move in opposite directions (Phillips Curve relationship).
GDP growth and inflation tend to move together during demand-driven periods.
Real interest rates responded with a lag to the inflation surge.
The COVID-19 pandemic acted as a clear structural break in the usual relationships.

Future extensions could include a larger set of countries, additional variables (money growth, commodity prices), or formal econometric tests for Granger causality and structural breaks around 2020.


📚 Sources

World Bank Open Data – World Development Indicators. https://data.worldbank.org/
Phillips, A. W. (1958). The Relation between Unemployment and the Rate of Change of Money Wage Rates in the United Kingdom, 1861–1957. Economica.
Okun, A. M. (1962). Potential GNP: Its Measurement and Significance.
Bank of Canada and Federal Reserve historical monetary-policy documentation.


👤 Author
Thuan Van Le

Bachelor of Computer Science

University of New Brunswick (UNB)


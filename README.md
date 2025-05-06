
# 🦠 COVID-19 Data Analysis Using Python

## 📌 Project Overview

This project focuses on performing an in-depth analysis of COVID-19 data in India using Python. It includes data cleaning, preprocessing, exploratory data analysis (EDA), and visualizations to understand the spread, recovery, mortality, and vaccination trends of the virus across Indian states.

## 📂 Datasets Used

1. **COVID-19 Cases Dataset**

   * Filename: `covid_19_india.csv`
   * Columns: Date, State/UnionTerritory, Confirmed, Cured, Deaths, etc.

2. **Vaccination Dataset**

   * Filename: `covid_vaccine_statewise.csv`
   * Columns: State, Total Doses Administered, Male/Female/Transgender doses, Age-wise vaccination stats, etc.

> Both datasets are publicly available from Indian government and health data repositories.

## 🛠️ Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly Express
* Jupyter Notebook

## 🧪 Data Processing

* Removed unnecessary columns (like `Sno`, `Time`, etc.)
* Converted date strings to datetime objects
* Calculated **active cases** as:
  `Active Cases = Confirmed - (Cured + Deaths)`
* Grouped and aggregated data for statewise analysis

## 📊 Visualizations

* Top 10 States with Highest Active Cases
* Top 10 States with Highest Death Toll
* Line Plot of Active Cases in Top 5 States Over Time
* Recovery Rate and Mortality Rate by State
* Vaccination Progress (from separate vaccine dataset)

## 🔍 Key Insights

* Maharashtra and Kerala had the highest number of confirmed and active cases.
* Recovery rates in most states were above 95%.
* Vaccination drive data shows steady progress in doses administered across different age groups and genders.

## 📁 How to Run

1. Clone the repository or download the `.ipynb` notebook.
2. Make sure the required CSV files (`covid_19_india.csv`, `covid_vaccine_statewise.csv`) are in the same directory.
3. Install dependencies (if not already installed):

   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
4. Run the notebook using Jupyter or any Python IDE that supports notebooks.

## 📌 Future Improvements

* Integrate more recent data and automate fetching updates.
* Add regional/village-level analysis if data is available.
* Use machine learning to predict future trends of COVID-19 spread.

## 👨‍💻 Author

**Md Muzamil Ahmad**
B.Tech in Computer Science Engineering (Data Science)
Location: Hyderabad, India

---

Would you like me to help format this into a downloadable `README.md` file?

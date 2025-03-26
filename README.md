# COVID-19 Trend Analysis

## 📌 Overview
This project analyzes COVID-19 trends using **Python**, **Pandas**, **Matplotlib**, **Seaborn**, and **Facebook Prophet** for time-series forecasting. It explores global COVID-19 trends, top-affected countries, and future predictions based on historical data.

## 📂 Dataset
- The dataset used: `covid_19_clean_complete.csv`
- Contains information on confirmed, recovered, and death cases across different countries and dates.

## 🛠 Libraries Used
- `pandas` – for data manipulation
- `numpy` – for numerical operations
- `matplotlib` & `seaborn` – for data visualization
- `prophet` – for forecasting future trends

## 📊 Data Processing Steps
1. Load and inspect the dataset.
2. Handle missing values (fill unknown provinces).
3. Convert the date column to `datetime` format.
4. Aggregate data by **Country/Region** and **Date**.
5. Analyze global trends using line plots.
6. Identify top 5 countries with the highest confirmed cases.
7. Use **Prophet** to predict future cases for the next 7 days.

## 📈 Visualizations
- **Global COVID-19 Trends Over Time**
  - A line plot showing trends for confirmed, recovered, active, and death cases.
- **Top 5 Affected Countries**
  - Displays the countries with the highest confirmed cases.
- **Future Prediction**
  - Uses Prophet to predict cases for the next 7 days with interactive plots.

## 🚀 How to Run the Project
1. **Clone the repository:**
   ```sh
   git clone https://github.com/YourGitHubUsername/covid-19-trend-analysis.git
   cd covid-19-trend-analysis
   ```
2. **Install dependencies:**
   ```sh
   pip install pandas numpy matplotlib seaborn prophet
   ```
3. **Run the Python script (Jupyter Notebook or .py file):**
   ```sh
   jupyter notebook
   ```
   Open the notebook and execute the cells.

## 📢 Results & Insights
- The number of **confirmed cases** has shown an upward trend.
- The **top affected countries** have significantly higher cases than others.
- **Forecasting** shows potential trends in upcoming days.

## 🔗 References
- COVID-19 dataset: [Kaggle](https://www.kaggle.com/datasets/)
- Prophet Documentation: [Facebook Prophet](https://facebook.github.io/prophet/)

## 💡 Future Enhancements
- Add regional analysis.
- Improve forecast accuracy with external data.
- Deploy as an interactive dashboard.



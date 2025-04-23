# SpaceX-Launch-Analysis-and-Prediction-Dashboard 🚀

This project is part of the Applied Data Science Capstone offered by IBM on Coursera. It focuses on exploring and analyzing SpaceX Falcon 9 launch data, visualizing key trends, and building predictive models to classify launch outcomes. The project also includes an interactive dashboard and geospatial analysis.

---

## 📁 Project Structure

- `Data Collection with Web Scraping.ipynb` — Scrapes SpaceX launch data from Wikipedia.
- `Data Collection Api .ipynb` — Collects launch site coordinates using SpaceX REST API.
- `Data wrangling .ipynb` — Cleans and merges datasets for analysis.
- `EDA with Visualization lab.ipynb` — Visual exploration using Matplotlib, Seaborn, Plotly.
- `EDA SQL Coursera.ipynb` — Performs SQL-based analysis using Jupyter SQL magic.
- `Machine Learning Prediction lab.ipynb` — Builds classification models to predict mission outcomes.
- `SpaceX Plotly.py` — Dash app code for interactive visual analytics.
- `spacex_launch_dash.csv` — Cleaned dataset used in dashboard.
- `dataset_part_1.csv` — Main dataset from Coursera used for analysis.
- `presentation.pdf` — Final project presentation.

---

## 🔍 Key Features

- **Data Wrangling**: Cleaned and unified data from Wikipedia, REST API, and CSVs.
- **EDA**: Visualizations of success rates by launch site, payload mass, and orbit types.
- **SQL Analysis**: Complex queries for launch outcomes and site comparisons.
- **Interactive Dashboard**: Built with Plotly Dash to explore site-specific success metrics.
- **Geospatial Analysis**: Folium maps highlighting launch sites and success rates.
- **Predictive Modeling**: Classification models (Logistic Regression, SVM) for outcome prediction.

---

## 📊 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Folium)
- Jupyter Notebooks
- SQL (via `%sql` magic)
- Dash (for web dashboard)
- BeautifulSoup & Requests (for web scraping)
- GitHub (for version control & collaboration)

---

## 🚀 How to Run the Dash App

```bash
python SpaceX\ Plotly.py

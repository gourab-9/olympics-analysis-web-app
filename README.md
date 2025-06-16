# 🏅 Olympics Data Analysis Dashboard

This is an interactive Streamlit app for analyzing over 120 years of Olympic Games history. You can explore medal tallies, trends, and patterns across nations, sports, and athletes using visualizations and data filters.

🔗 **Live App**: [Click to Open](https://u7gsda7uvud5hs4hdzcmwv.streamlit.app/)

---

## 📊 Features

### 📌 1. Medal Tally
- View medal tally by year, country, or both
- Dynamic titles and filters
- Interactive data table

### 📌 2. Overall Analysis
- Stats: Total editions, sports, events, cities, nations, athletes
- Trendlines: Participating nations, events, and athletes over time
- Heatmaps: Events per sport per year
- Most successful athletes (by medals, optionally filtered by sport)

### 📌 3. Country-wise Analysis
- Year-wise medal trend for selected country
- Heatmap of strong sports by country
- Top 10 athletes from a country

### 📌 4. Athlete-wise Analysis
- Age distribution of all medalists
- Gold medalist age distribution by sport
- Scatter plot: Height vs Weight by sport
- Gender participation trends over years

---

## 🛠️ Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **Backend**: Python
- **Visualization**: Plotly, Seaborn, Matplotlib
- **Data Handling**: Pandas
- **Custom Modules**: `preprocessor.py`, `helper.py`

---
## 🗂️ Project Structure

```text
📦 olympics-analysis/
┣ 📄 olympics_app.py # Main Streamlit app
┣ 📄 preprocessor.py # Data cleaning module
┣ 📄 helper.py # Utility functions
┣ 📁 data/
┃ ┣ 📄 athlete_events.csv
┃ ┗ 📄 noc_regions.csv
┣ 📄 requirements.txt
┗ 📄 README.md
```
---
## 📦 requirements.txt


streamlit
pandas
plotly
matplotlib
seaborn




---
## 💻 Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/olympics-analysis.git
cd olympics-analysis

# 2. (Optional) Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run olympics_app.py

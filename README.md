## How to Set Up Locally
1. Clone or download this repository to your computer.
2. Place the `metadata.csv` file (WHO COVID-19 global summary) in the project folder.
3. Open a terminal in the project folder.
4. Install the required Python packages:
   ```powershell
   pip install -r requirements.txt
   ```
5. Start the Streamlit app:
   ```powershell
   streamlit run app.py
   ```
6. Open the local URL (e.g., `http://localhost:8501`) in your browser to view and interact with the dashboard.
## How It Works Locally
When you run the app locally, Streamlit launches a web dashboard in your browser. You can:
- Filter COVID-19 data by WHO region using the sidebar
- View bar charts of the top 10 countries by cumulative cases and deaths
- Browse a sample data table for quick insights

All features are interactive and update instantly as you change filters.
# WHO COVID-19 Global Data Explorer

This project is a simple Streamlit dashboard for exploring global COVID-19 case and death statistics by country and region, using WHO data.

## Features
- Interactive charts for top 10 countries by cumulative cases and deaths
- Region filter in the sidebar
- Sample data table


## How to Run Locally
1. Place `metadata.csv` (WHO COVID-19 global summary) in the project folder.
2. Install required packages:
   ```powershell
   pip install pandas matplotlib streamlit
   ```
3. Start the app:
   ```powershell
   streamlit run app.py
   ```
4. After running the command, Streamlit will display a local URL in the terminal (e.g., `http://localhost:8501`).
5. Open this URL in your web browser to access the dashboard.


## How to Access on Streamlit Cloud
This project is deployed at: [https://covida.streamlit.app/](https://covida.streamlit.app/)
Anyone with this link can access the dashboard online without installing anything locally.

## File Structure
- `app.py` — Streamlit dashboard code
- `metadata.csv` — WHO COVID-19 global summary data

## Notes
- This app is designed for the WHO global COVID-19 summary, not the CORD-19 research dataset.
- For other datasets, update the code and README accordingly.

## Author
Charlesomondi-dot

# EcoBuddy AI

EcoBuddy AI is a polished Streamlit web application for tracking and analyzing your personal carbon footprint. The app uses lifestyle inputs to calculate emissions, generate an eco score, display interactive charts, and produce a downloadable PDF report.

## ?? Features

- Friendly lifestyle input form for transport, electricity, diet, and flights
- Annual carbon footprint calculation with contributor breakdown
- Eco score and badge system for instant impact feedback
- Animated and modern dashboard layout with insights and recommendations
- Interactive Plotly charts for emission sources and trend tracking
- PDF report export for sharing and record keeping
- Local assessment history to monitor progress over time

## ?? Installation

1. Clone or download the repository

```bash
cd c:\Users\neeru\OneDrive\Desktop\eco-buddy-ai\eco-buddy-ai
```

2. Create a virtual environment (recommended)

```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

## ?? Run the app

```bash
streamlit run app.py
```

Then open the local Streamlit link shown in your terminal.

## ?? Project Structure

- `app.py` — Main Streamlit application and UI
- `database.py` — Database initialization and assessment persistence
- `emissions.py` — Carbon footprint calculation logic
- `recommendations.py` — Eco recommendation generation
- `requirements.txt` — Python project dependencies
- `test_db.py`, `test_emissions.py`, `test_recommendations.py` — Unit tests

## ?? Notes

- The app uses `Streamlit` for the UI, `Plotly` for charts, and `ReportLab` for PDF export.
- If you need a lighter install, install only the packages required for the app and UI.

## ?? Improvements

If you'd like, I can also add:

- a dark/light theme toggle
- more advanced emissions categories
- better PDF styling and additional report sections
- user authentication and cloud storage

Enjoy your eco journey! ??

# GameStats — GTA 5 Performance & Hardware Analyzer

GameStats is a Python-based project that analyzes gaming-session data and presents performance insights through an interactive Streamlit dashboard.

## Features
- FPS, CPU, GPU, RAM and GPU temperature summaries
- Player leaderboard, KDA and win-rate calculations
- Charts, filters, descriptive statistics and correlation analysis
- Jupyter Notebook practicals using the same CSV dataset

## Files
- `app.py` — Streamlit dashboard
- `game_stats.csv` — dataset used by the dashboard and notebook
- `GameStats_Backend.ipynb` — data cleaning, analysis and visualizations
- `requirements.txt` — required Python packages
- `index.html`, `style.css`, `script.js` — optional standalone web frontend

## Run the dashboard
```bash
pip install -r requirements.txt
streamlit run app.py
```

Keep `game_stats.csv` in the same folder as `app.py`. Open the notebook in Jupyter or Google Colab to run the analysis.

**Note:** The dataset contains sample project data; it is not verified live gameplay data or live hardware monitoring.

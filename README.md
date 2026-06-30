# -AI_Sales_Analyser
# AI Sales Data Analyser

An AI-powered sales data analysis tool built with Python and 
Machine Learning — runs completely free on your laptop.

## What This Project Does
- Loads raw retail sales data automatically
- Cleans and transforms data using Pandas
- Calculates business KPIs (revenue, averages, trends)
- Uses Machine Learning (Isolation Forest) to detect unusual transactions
- Generates 4 charts automatically
- Saves a full business insights report

## AI Features
- Anomaly Detection using Scikit-learn Isolation Forest
- Automatically flags unusual transactions (potential fraud)
- No API key needed — runs 100% locally and free

## Results
- Total Revenue: $3,865.74
- Top Category: Electronics ($2,129.96)
- Top City: Atlanta ($1,962.40)
- AI detected 2 anomalous transactions:
  - T001 → Electronics → $1,079.98 (high value anomaly)
  - T007 → Groceries → $59.90 (unusual quantity anomaly)

## Tools Used
- Python 3.14
- Pandas (data cleaning and analysis)
- Matplotlib (chart generation)
- Scikit-learn (machine learning anomaly detection)
- GitHub (version control)

## Files
- `Ai_analyser.py` → main Python script
- `sales_data.csv` → raw sales data
- `sales_dashboard.png` → auto-generated charts
- `ai_report.txt` → AI generated business report

## How to Run
1. Install libraries: `pip install pandas matplotlib scikit-learn`
2. Run: `python Ai_analyser.py`
3. Check output files for charts and reportAI-powered sales data analyser using Python and Machine Learning

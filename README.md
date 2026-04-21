# 📊 Trader Performance vs Market Sentiment Analysis

This project analyzes how market sentiment (Fear/Greed) impacts trader behavior and performance using Hyperliquid trading data.

---

## 📁 Dataset

The repository includes both required datasets:

- `historical_data.csv` → Trader data  
- `fear_greed_index.csv` → Market sentiment data  

---

## 🚀 How to Run (Google Colab)

Follow these steps to run the project:

### 1. Open Google Colab
Go to: https://colab.research.google.com

---

### 2. Upload Notebook
Upload the provided `.ipynb` file into Colab.

---

### 3. Upload Dataset Files
Run the first cell:

```python
from google.colab import files
files.upload()

Then upload the following files:

historical_data.csv
fear_greed_index.csv

4. Run the Notebook

Execute all cells step by step:

Data cleaning and preprocessing
Timestamp conversion and dataset alignment
Feature engineering (PnL, win rate, trade size, etc.)
Data analysis and visualizations
Trader segmentation using K-Means clustering
Predictive modeling using Random Forest
5. Launch the Dashboard (Gradio)

In the final cell, a Gradio interface will be generated.

👉 Click on the provided link to open the interactive dashboard.

The dashboard allows you to:

Analyze trader performance based on sentiment
View average PnL and win rate
Predict whether a trade will be profitable

📈 Key Features
Sentiment-based performance analysis
Trader behavior insights
K-Means clustering for trader segmentation
Random Forest model for prediction
Interactive dashboard using Gradio

💡 Key Insights
Profitability is highest during Greed sentiment
Win rate decreases during Fear conditions
Neutral markets show the weakest performance
Efficient traders outperform high-capital traders

🚀 Strategy Recommendations
Increase exposure during Greed, focusing on high-quality trades
Reduce leverage and risk during Fear
Avoid trading in Neutral sentiment
Focus on trade efficiency rather than increasing capital

🛠️ Tech Stack
Python (Pandas, NumPy)
Matplotlib
Scikit-learn
Gradio

📌 Note

Ensure both CSV files are uploaded before running the notebook.
The dashboard will only work after executing all cells successfully.


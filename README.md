# Junior Data Scientist - Trader Behavior Insights

---

##  Project Overview

The objective of this assignment is to analyze the relationship between trader behavior on the Hyperliquid platform and overall market sentiment. By merging and analyzing two distinct datasets, this project uncovers key patterns in trader profitability, volume, and decision-making during different market phases.

### Datasets Used:

1.  **Bitcoin Fear & Greed Index**
    -   **Columns Used:** `date`, `classification` (Fear/Greed)
    -   **Description:** Provides daily market sentiment classifications.
    -   **Link:** [Download Fear & Greed Data](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)

2.  **Historical Trader Data from Hyperliquid**
    -   **Columns Used:** `time`, `closedpnl`, `size`, `side` (Buy/Sell)
    -   **Description:** Contains granular, real-time trading data for individual accounts.
    -   **Link:** [Download Historical Trader Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

---

##  How to Run the Project

### Step 1 – Prepare the Environment
1.  Download both datasets from the links provided above and place them in the `csv_files/` directory.
2.  Open [Google Colab](https://colab.research.google.com/).
3.  Upload the entire project folder or, at a minimum, the `notebook_1.ipynb` and the `csv_files` folder to your Colab environment.

### Step 2 – Execute the Notebook
1.  Open `notebook_1.ipynb` in your Colab environment.
2.  Run all cells sequentially from top to bottom (`Runtime` -> `Run all`).
3.  The notebook will automatically process the data and generate all visualizations.

### Step 3 – Review Outputs
- All visual outputs (graphs and charts) will be automatically saved to the `outputs/` directory.
- The final analysis and insights are summarized in `ds_report.pdf`.

---

##  Key Insights from the Analysis

### 1. Profitability is Driven by Sentiment
Traders exhibit significantly higher median profitability during market **'Greed'**. Conversely, the median trader experiences a net loss during periods of market **'Fear'**, suggesting difficulty in navigating volatile or declining markets.

### 2. Trading Volume Increases with Greed
The average trade size (in USD) is notably larger when the market is in a 'Greed' phase. This indicates higher capital allocation and risk-taking, likely driven by bullish conviction or "Fear of Missing Out" (FOMO).

### 3. Bullish Behavior Aligns with Positive Sentiment
While 'Buy' orders are dominant across all conditions, the proportion of 'Buy' trades sees a slight increase during 'Greed' periods, aligning with the overall positive outlook of the market.

### 4. Strategic Recommendations
-   **Risk Management:** Traders should be particularly cautious with position sizing during 'Greed' phases, as increased volume amplifies both potential gains and losses.
-   **Platform Features:** Trading platforms could implement sentiment-based alerts to help users recognize how market psychology might be influencing their decisions.

---

##  Repository Structure
- `notebook_1.ipynb` – Complete analysis notebook.
- `csv_files` – The Requied Datasets
- `outputs/` – Folder containing all visualizations:
  - `trader_pnl_distribution.png`  
  - `pnl_by_sentiment.png`  
  - `size_by_sentiment.png`  
  - `trades_by_sentiment.png`  
- `ds_report.pdf` – A detailed summary of the methods, findings, and recommendations.
- `README.md` – This documentation file.

---
##  Notes

- Ensure that you upload the datasets when running the notebook.
- The notebook can be run from start to finish without errors.
- The visual outputs are stored in the `outputs/` folder and are referenced in the report.
- This work has been completed following the assignment guidelines provided.

---

##  Contact

**Author:** Srujan Kumar  
**Email:** srujankumaryallampalli@gmail.com 


---

##  License

This project is for educational purposes and has been completed as part of the recruitment process for the Junior Data Scientist role.

---

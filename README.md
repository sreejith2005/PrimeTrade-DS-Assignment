# Data Science Assignment: Trader Behavior vs. Market Sentiment

This project analyzes the relationship between trader behavior and market sentiment, as per the assignment instructions for the Web3 Trading Team internship.
<img width="1000" height="600" alt="volume_by_sentiment" src="https://github.com/user-attachments/assets/fa157a06-b448-4011-a255-75d475065876" />
<img width="1000" height="600" alt="total_pnl_by_sentiment" src="https://github.com/user-attachments/assets/c940339a-dc91-4161-8ba5-a1d54479c5e7" />

## Project Structure

The directory is structured according to the submission guidelines:

```ds_<candidate_name>/
├── notebook_1.ipynb       # Main Google Colab notebook with all analysis.
├── outputs/
│   ├── total_pnl_by_sentiment.png
│   └── volume_by_sentiment.png
├── ds_report.txt         # Final report summarizing insights.
```


## How to Run

1.  **Open the Notebook**: Open `notebook_1.ipynb` in Google Colab.
2.  **Upload Data**: Upload `historical_data.csv` and `fear_greed_index.csv` to the Colab session.
3.  **Execute Code**: Run all cells in the notebook from top to bottom.
4.  **Outputs**: The script will generate two chart images (`.png` files) and save them to the `outputs/` folder, which should be created locally. Download these from Colab and place them in the local folder.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn

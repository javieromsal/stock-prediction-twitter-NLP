# Stock-prediction-twitter-NLP 📈🤖🐦
This project dives into the world of **social media** sentiment to uncover its potential influence on the global economy.
By analyzing tweets, we explore how public sentiment on **Twitter may correlate with stock market trends**, aiming to predict future market movements.
Can the pulse of social media really shape financial decisions? Let’s find out!

## 📌 Overview
This project aims to understand the impact of public sentiment on stock market prices, using Twitter data. By analyzing tweets related to a specific company (in this case, Tesla), we explore whether there's a relationship between social media sentiment and market movements, and how this can help predict stock price fluctuations.

The dataset includes:

📊 Dataset 1: Tesla Stock Market Data (Daily open-close for 2022).

🌍 Dataset 2: Global Mentions Data of Tesla on Twitter(153,000 rows, April - December 2022). This data was gathered using the Tweepy API.

By applying Sentiment Analysis to the Twitter data, we identified correlations between the public mood and Tesla’s stock performance. Through Granger Causality testing, we found a time-lag relationship between Twitter sentiment and stock price changes, particularly with a 4-day lag. Lastly, using Random Forest, we built a predictive model, which successfully predicted a rise in Tesla’s stock price 4 days out from December 11, 2022.

## 📂 Project Structure
- `notebooks/`: Jupyter Notebooks with step-by-step analysis.
- `data/`: Datasets.
- `src/`: Python scripts used for analysis.
- `visuals/`: Charts and graphs.

## 🚀 How to Run
1. Clone the repo:  
   ```bash
    git clone https://github.com/javieromsal/stock-prediction-twitter-NLP.git
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
3. Open Jupyter Notebook and follow the steps.

## 🔑 Key Insights
- **Sentiment vs. Stock Prices:** Through sentiment analysis, we discovered a correlation between public opinions on Twitter and stock price movements. The positive or negative mood surrounding Tesla had a noticeable effect on its stock, demonstrating how social media sentiment can impact financial markets.

- **Granger Causality:** The Granger Causality test revealed that Twitter sentiment can predict stock price changes, with a 4-day lag. This finding suggests that public sentiment may have a delayed influence on the stock market, making it a potential indicator for future price trends.

- **Predictive Power of Twitter Sentiment:** By using Random Forest classification, we were able to predict whether Tesla’s stock price would go up or down in the following days, with promising accuracy. The model successfully identified an upward trend for Tesla’s stock price, forecasting an increase on December 11, 2022.

- **Behavioral Economics in Action:** This study highlights the importance of behavioral economics, showing how emotions and public opinion shape decision-making in financial markets. The findings align with the work of Professor Johan Bollen and his research on Twitter mood’s impact on stock prices.

## 🤝 Contributing
This project was a collaborative effort between me and my amazing colleague, Sara 🙌. Together, we explored the connection between Twitter sentiment and stock market trends using data analysis and behavioral economics.

Our main reference was the paper **“Twitter mood predicts the stock market”** (Bollen et al., 2011), which provided the foundation for our analysis.

Feel free to fork the repo or submit a pull request if you’d like to contribute!

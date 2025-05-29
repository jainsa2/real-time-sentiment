# Twitter Sentiment Analysis

This project performs **real-time sentiment analysis** on tweets fetched from Twitter using a keyword or hashtag. It uses Natural Language Processing (NLP) to classify tweets into **Positive**, **Negative**, or **Neutral** categories and presents visual insights using graphs and word clouds.

## 📌 Project Features

- 🐦 Fetch live tweets from Twitter API using any keyword or hashtag
- 🧠 Analyze sentiment using TextBlob (or VADER)
- 📊 Visualize sentiment distribution (pie chart, bar chart)
- ☁️ Generate word clouds of commonly used words
- 🌐 Optional: Streamlit app for user interaction

## 🧰 Tech Stack

- **Languages**: Python
- **Libraries**: Tweepy, TextBlob, Pandas, Matplotlib, Seaborn, WordCloud
- **Optional**: Streamlit (for the web app)

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/twitter-sentiment-analysis.git
cd twitter-sentiment-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Set up Twitter API credentials
Create a file named `config.py` and add your credentials:
```python
API_KEY = "your_api_key"
API_SECRET = "your_api_secret"
ACCESS_TOKEN = "your_access_token"
ACCESS_TOKEN_SECRET = "your_access_token_secret"
```

### 4. Run the analysis
You can use either the notebook or the Streamlit app:

#### Option A: Run the Jupyter Notebook
```bash
jupyter notebook notebooks/sentiment_analysis.ipynb
```

#### Option B: Run the Streamlit App (Optional)
```bash
streamlit run app/streamlit_app.py
```

## 📁 Project Structure

```
twitter-sentiment-analysis/
├── data/                  # Stores fetched tweets (CSV format)
├── notebooks/             # Jupyter Notebooks
│   └── sentiment_analysis.ipynb
├── src/                   # Python source files
│   └── sentiment.py
├── app/                   # Streamlit app (optional)
│   └── streamlit_app.py
├── config.py              # Twitter API credentials
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── LICENSE
```

## 📊 Sample Output

![Pie Chart](images/sentiment_pie.png)
![Word Cloud](images/wordcloud.png)

## 📜 License

This project is licensed under the MIT License.

## 🙋‍♀️ Author

**Shruti Ajay Jain**  
B.Tech CSE (Data Science), Shri Ramdeobaba College of Engineering and Management  
LinkedIn: [linkedin.com/in/shruti-ajay-jain](https://linkedin.com/in/shruti-ajay-jain)

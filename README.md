# Sentiment-Analyzer
A Python tool that fetches live market data, calculates 7-day and 30-day moving averages, and visualizes stock price trends using yfinance and Matplotlib.



# 🧠 Customer Feedback Sentiment Analyzer

A Natural Language Processing (NLP) project that automatically reads customer reviews, determines their emotional tone, and visually highlights the most common complaints using a Word Cloud.

## 🚀 Key Features
* **Automated Text Classification:** Uses the `TextBlob` library to analyze text polarity and classify sentences as Positive, Negative, or Neutral.
* **Data Pipeline & Export:** Processes raw CSV data, appends the calculated sentiments, and automatically exports the clean, updated dataset to an Excel file (`Sentiment_upd.xlsx`).
* **Targeted Insights:** Filters the dataset to isolate negative reviews for deeper analysis.
* **Visualizing Pain Points:** Generates a custom, color-coded Word Cloud from the negative feedback to instantly identify the most frequently used words in customer complaints.

## 🛠️ Tech Stack & Libraries
* **Python 3**
* **[TextBlob](https://textblob.readthedocs.io/):** For out-of-the-box NLP and sentiment polarity scoring.
* **[WordCloud](https://pypi.org/project/wordcloud/):** To generate the visual representation of text data.
* **[Pandas](https://pandas.pydata.org/):** For reading the CSV, manipulating dataframes, and exporting to Excel.
* **[Matplotlib](https://matplotlib.org/):** For plotting the final Word Cloud image.

## 📦 Installation

Clone this repository to your local machine, then install the required NLP and visualization libraries:

``bash
pip install pandas textblob wordcloud matplotlib openpyxl

(Note: openpyxl is required for Pandas to successfully export data to Excel files).

💻 Usage
Ensure the Sentiment_Analysis .csv dataset is located in the exact same folder as the Python script.

Run the Jupyter Notebook or Python script.

The program will automatically generate a new Sentiment_upd.xlsx file in your directory containing the scored reviews.

A Word Cloud image will display on your screen, highlighting the most common negative keywords from the dataset.


Copy and paste this text into the `README.md` file of your new, separate Sentiment Analysis repository.

```markdown
# 🧠 Customer Feedback Sentiment Analyzer

A Natural Language Processing (NLP) project that automatically reads customer reviews, determines their emotional tone, and visually highlights the most common complaints using a Word Cloud.

## 🚀 Key Features
* **Automated Text Classification:** Uses the `TextBlob` library to analyze text polarity and classify sentences as Positive, Negative, or Neutral.
* **Data Pipeline & Export:** Processes raw CSV data, appends the calculated sentiments, and automatically exports the clean, updated dataset to an Excel file (`Sentiment_upd.xlsx`).
* **Targeted Insights:** Filters the dataset to isolate negative reviews for deeper analysis.
* **Visualizing Pain Points:** Generates a custom, color-coded Word Cloud from the negative feedback to instantly identify the most frequently used words in customer complaints.

## 🛠️ Tech Stack & Libraries
* **Python 3**
* **[TextBlob](https://textblob.readthedocs.io/):** For out-of-the-box NLP and sentiment polarity scoring.
* **[WordCloud](https://pypi.org/project/wordcloud/):** To generate the visual representation of text data.
* **[Pandas](https://pandas.pydata.org/):** For reading the CSV, manipulating dataframes, and exporting to Excel.
* **[Matplotlib](https://matplotlib.org/):** For plotting the final Word Cloud image.

## 📦 Installation

Clone this repository to your local machine, then install the required NLP and visualization libraries:

```bash
pip install pandas textblob wordcloud matplotlib openpyxl

```

*(Note: `openpyxl` is required for Pandas to successfully export data to Excel files).*

## 💻 Usage

1. Ensure the `Sentiment_Analysis .csv` dataset is located in the exact same folder as the Python script.
2. Run the Jupyter Notebook or Python script.
3. The program will automatically generate a new `Sentiment_upd.xlsx` file in your directory containing the scored reviews.
4. A Word Cloud image will display on your screen, highlighting the most common negative keywords from the dataset.

```

When setting up this new repository, make sure to upload exactly three things: this `README.md` file, your Jupyter Notebook code (`.ipynb`), and the `Sentiment_Analysis .csv` file so visitors have the data needed to actually test your code.

<FollowUp label="Want to add a web interface to this sentiment analyzer?" query="How do I turn this sentiment analysis code into an interactive Streamlit web app?"/>

``


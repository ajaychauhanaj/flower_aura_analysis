🌸 FlowerAura Reviews Sentiment Analysis

This project performs web scraping, sentiment analysis, and visualization on customer reviews of a bouquet product from FlowerAura.
The goal is to understand customer satisfaction by analyzing review text polarity and subjectivity, and presenting insights through charts and word clouds.

📌 Project Overview

Scrapes customer reviews from a FlowerAura product page (10 Red Roses Bouquet).

Cleans and structures review data (name, city, date, rating, review text).

Performs sentiment analysis using TextBlob.

Classifies reviews as Positive or Negative.

Visualizes sentiment distribution and word frequency.

⚙️ Features

Automated multi-page review scraping (50 pages).

Data cleaning & date normalization.

Sentiment polarity & subjectivity scoring.

Positive vs Negative classification.

Countplot of sentiment distribution.

WordClouds for positive & negative reviews.

🧰 Tech Stack

Python

BeautifulSoup (Web Scraping)

Requests (HTTP)

Pandas & NumPy (Data Processing)

TextBlob (Sentiment Analysis)

Seaborn & Matplotlib (Visualization)

WordCloud (Text Visualization)

📂 Dataset Fields

After scraping and preprocessing, the dataset contains:

Column	Description
Name	Reviewer name
City	Reviewer location
Posted_on	Review date
Review	Review text
Rating	Star rating
Polarity	Sentiment polarity score
Subjectivity	Subjectivity score
Score	Positive / Negative label
🚀 Workflow

Scrape Reviews

Loop through 50 review pages.

Extract reviewer info and text.

Data Cleaning

Normalize date format.

Convert rating to numeric.

Sentiment Analysis

Compute polarity & subjectivity with TextBlob.

Label sentiment.

Visualization

Sentiment count plot.

Positive & negative word clouds.

📊 Example Outputs

Sentiment distribution bar chart.

Positive review word cloud.

Negative review word cloud.

Overall sentiment classification (mean polarity).

▶️ How to Run
# Clone repository
git clone https://github.com/yourusername/floweraura-sentiment-analysis.git

# Install dependencies
pip install beautifulsoup4 requests pandas numpy textblob seaborn matplotlib wordcloud

# Run notebook
jupyter notebook flower_aura_sentiment_analysis.ipynb
📈 Key Insight

The notebook calculates the average polarity of all reviews to determine whether overall customer sentiment toward the product is positive or negative.

📝 Future Improvements

Add neutral sentiment class.

Scrape multiple products for comparison.

Deploy dashboard (Streamlit/Power BI).

Topic modeling of reviews.

Time-based sentiment trends.

👤 Author

Ajay Chauhan
Data Analytics & Finance Enthusiast

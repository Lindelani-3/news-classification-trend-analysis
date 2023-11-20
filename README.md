# News Article Classification and Trend Analysis

We'll define a hypothetical scenario for our News Article Classification and Trend Analysis project focused on the finance sector in Africa. This will include the client, their problem, the challenges addressed, business questions, and related KPIs.

## Client
Client Name: Pan-African Financial Insights (PAFI)

Industry: Financial Analysis and Consulting

Region: Africa

## Problem Statement
PAFI aims to provide comprehensive financial analytics and insights across various African markets. They lack a real-time, data-driven approach to understanding financial news trends and sentiments across the continent, which are crucial for advising clients on investment and policy decisions.

## Challenges Addressed
Volume of Data: Handling and analyzing the large volume of news data generated daily across multiple countries and sources.

Real-Time Analysis: Providing up-to-date insights from the latest news, as financial markets are highly dynamic and sensitive to current events.

Sentiment Analysis: Accurately gauging the sentiment of financial news to understand market sentiment.

Language and Regional Variations: Catering to a diverse continent with multiple languages and regional contexts.

Data Reliability and Bias: Ensuring the reliability and objectivity of the news sources and the insights derived from them.

## Business Questions

What are the current trending financial topics in Africa?

How do financial news sentiments vary across different African countries or regions?

What is the correlation between major financial news events and market movements?

Which news sources are most influential in the African financial markets?

How do financial news trends and sentiments compare between African countries and the global market?

## Related KPIs

**Volume of Articles:** Number of finance-related articles published per time period.

**Sentiment Analysis Scores:** Distribution of sentiment (positive, negative, neutral) across articles.

**Trend Identification:** Frequency of specific financial topics or keywords over time.

**Source Influence:** Engagement metrics (like shares, comments) of articles from different news sources.



## Approach

Web Scrapping: Used BeautifulSoup to extract the full content of articles (allowed by the website's `robots.txt`) given the url provided by our News.org API data.

Topic Classification: The dataset has been classified into various topics using different clustering methods (KNN, Hierarchical, GMM). Each method reveals different thematic focuses, such as Environment, Technology, Politics, Finance, and Entertainment.

Sentiment Analysis: Sentiments of the news articles have been analyzed and categorized (e.g., negative, positive, very positive). This offers insights into the general sentiment around various topics.



## Implementation in the Context of the Project

Data Acquisition: Use NewsAPI to gather finance-related news articles from across Africa.

Data Processing: Clean and preprocess the data, considering linguistic and contextual diversity.

![news trend preview data](https://github.com/Lindelani-3/news-classification-trend-analysis/assets/99859713/640476e9-0019-4b42-a372-d75815948bdc)

Analysis and Classification: Apply NLP techniques for sentiment analysis and topic classification.

![news trend preview databricks](https://github.com/Lindelani-3/news-classification-trend-analysis/assets/99859713/b0904dcf-59e5-4a2c-a5a2-20637a43b558)

Visualization and Reporting: Develop dashboards to visualize trends, sentiments, and other KPIs.

![news trend preview visual](https://github.com/Lindelani-3/news-classification-trend-analysis/assets/99859713/f8fc17cf-979e-47ce-aa8b-647a49cff160)

Scalability and Future Extensions: Plan for real-time data processing and integration with financial market data for deeper analysis by using Databricks, PySpark, and other related AWS Services.

## Technologies Used

Python (Pandas, NumPy, scikit-learn, Gensim, NLTK, Torch, BeautifulSoup, etc), Jupyter Notebook, Matplotlib, Databricks, AWS (S3, EC2, RDS).


## Value

Investment Guidance: Utilized sentiment and trend analysis to guide investment strategies. Positive sentiment in certain financial sectors can indicate growth opportunities, while negative sentiment could signal risk.

Trend Forecasting: We could use historical data trends to forecast future market movements or interest areas in the financial sector, using forecsating models like AMIRA.

Targeted Marketing: Insights can be used to tailor marketing strategies, focusing on sectors or topics that are currently trending or have positive sentiments.

Product Development: PAFI can also develop new services or products based on identified market needs or gaps revealed through trend analysis.

Integrate Market Data: In the future we can also incorporate financial market data (e.g., stock prices, currency rates) to correlate news sentiments with actual market movements.

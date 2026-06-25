

## Task 04 - Twitter Sentiment Analysis and Visualization

### Objective

Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics, products, brands, or events.

### Dataset

Twitter Sentiment Analysis Dataset

The dataset contains tweets categorized into different sentiment classes:

* Positive
* Negative
* Neutral
* Irrelevant

### Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* WordCloud

### Project Workflow

#### 1. Data Collection

* Loaded Twitter sentiment dataset.
* Examined dataset structure and columns.

#### 2. Data Cleaning

* Removed missing values.
* Cleaned tweet text by:

  * Converting text to lowercase
  * Removing URLs
  * Removing mentions and hashtags
  * Removing punctuation and special characters
  * Removing stopwords

#### 3. Exploratory Data Analysis (EDA)

* Analyzed sentiment distribution.
* Visualized sentiment percentages.
* Identified most discussed brands and topics.
* Explored sentiment trends across brands.

#### 4. Text Analysis

* Generated overall word cloud.
* Generated positive sentiment word cloud.
* Generated negative sentiment word cloud.
* Generated neutral sentiment word cloud.

#### 5. Visualization

* Bar Charts
* Pie Charts
* Heatmaps
* Word Clouds
* Brand-wise Sentiment Analysis

### Key Insights

* Public opinion varies significantly across brands and topics.
* Certain brands receive predominantly positive feedback.
* Some brands attract a higher proportion of negative sentiment.
* Frequently occurring words reveal major discussion themes.
* Sentiment analysis provides valuable insights into customer perception and market trends.

### Results

The project successfully analyzed social media sentiment and visualized public opinion patterns using various data visualization techniques.

### Files Included

```text
PRODIGY_DS_04/
│
├── Twitter_Sentiment_Analysis.ipynb
├── twitter_training.csv
├── cleaned_twitter_sentiment.csv
├── README.md
│
└── screenshots/
    ├── sentiment_distribution.png
    ├── pie_chart.png
    ├── wordcloud.png
    ├── positive_wordcloud.png
    ├── negative_wordcloud.png
    └── heatmap.png
```

### Author

Fateen Malik

### Internship

Prodigy InfoTech - Data Science Internship

### Outcome

Successfully performed sentiment analysis and visualization on Twitter data to understand public opinion and sentiment trends toward various brands and topics.

# Sentiment Analysis using PySpark
This project centers on sentiment analysis of social media platforms like Twitter and Reddit, with a focus on discerning public sentiment toward various subjects. Social media platforms serve as dynamic arenas for individuals to express opinions, providing real-time insights into prevailing sentiments. By analyzing these sentiments, valuable insights into trending topics and public mood can be gleaned.

The primary aim of the project is to implement and compare contemporary machine learning text classification algorithms, leveraging the vast amounts of textual data available on social media. This allows for the accurate prediction of sentiment conveyed within the text.

For optimal accessibility and utilization of project files, it is recommended to utilize Jupyter Notebooks or the Anaconda Distribution, avoiding direct file access for a smoother workflow.
## Overview
This project focuses on performing sentiment analysis using PySpark. The data is scraped from Reddit and Twitter, then cleaned and analyzed. The cleaned and analyzed data is then used for sentiment analysis.

## Project Structure
- `data/`: Contains the scraped data from Reddit and Twitter.
- `notebooks/`: Jupyter notebooks used for data cleaning, analysis, and model training.
- `src/`: Source code for the sentiment analysis project.
- `README.md`: This file providing an overview of the project.

## Data Collection
- Data is collected from Reddit and Twitter using appropriate APIs or web scraping techniques.

## Data Cleaning and Analysis
- Cleaned and analyzed the scraped data.
- Performed sentiment labeling.

## Sentiment Analysis Pipeline
- Imported the cleaned and analyzed data.
- Preprocessed the data.
- Created a model pipeline with the following stages:
  1. RegexTokenizer
  2. StopWordsRemover
  3. CountVectorizer
  4. StringIndexer

## Model Training and Evaluation
- Split the dataset into training and testing sets.
- Trained and evaluated the model using various machine learning algorithms, including:
  - Logistic Regression
  - Naive Bayes
  - Decision Tree Classifier
  - Random Forest Classifier

## Dependencies
- Python 3.x
- PySpark
- Jupyter Notebook (for data exploration and analysis)
- Other necessary libraries as mentioned in the `requirements.txt` file.

## How to Use
1. Clone this repository.
`git clone [https://github.com/yourusername/sentiment-analysis-pyspark.git](https://github.com/yashnilapwar/Sentiment-Analysis-using-Pyspark.git)`
2. Install the required dependencies using `pip install -r requirements.txt`.



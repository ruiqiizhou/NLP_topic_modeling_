# Topic Modeling and Sentiment Analysis of The New York Times Comments

## Project Overview

This project explores the evolution of topics and sentiment in the comments section of The New York Times articles from April 2017 to April 2018. Using advanced natural language processing techniques, the analysis identifies key themes and sentiment trends to understand public opinion and discourse dynamics during this period.

## Purpose

The purpose of this analysis is to uncover how topics and sentiment in public comments have evolved over the specified time frame. Insights from this study can help in understanding the changing landscape of public opinion, potentially guiding editorial decisions and content strategies.

## Data Description

The dataset comprises comments extracted from The New York Times articles, spanning from April 2017 to April 2018. Each comment entry includes the following information:

Comment ID: A unique identifier for each comment.
Article ID: Identifier linking the comment to a specific article.
User ID: Identifier for the user who made the comment.
Comment Text: The text content of the comment.
Timestamp: The date and time when the comment was posted.

Link：https://www.kaggle.com/datasets/aashita/nyt-comments

## Code Description

The analysis is conducted using Python, with the Jupyter Notebook Topic_modeling.ipynb containing all the code and commentary necessary to perform the topic modeling and sentiment analysis. Key components of the code include:

Data Preprocessing: Cleaning and preparing text data for analysis.

Topic Modeling: Using Nonnegative Matrix Factorization (NMF) to identify prevalent topics within the comments.

Sentiment Analysis: Calculating sentiment scores to determine the overall sentiment of comments associated with each topic.

Visualization: Generating visualizations to display the trends and results of the topic modeling and sentiment analysis.

## How to Use

To run this project:

Clone the repository to your local machine.

Ensure that you have Python installed, along with the libraries numpy, pandas, matplotlib, scikit-learn, and nltk.

Open the Topic_modeling.ipynb notebook in a Jupyter environment.

Execute the cells sequentially to observe the analysis process and results.

## Dependencies

Python 3.8+
NumPy
pandas
Matplotlib
scikit-learn
NLTK
Contributors

This project is maintained by [Ruiqi Zhou], and contributions to the code or analysis are welcome. For major changes, please open an issue first to discuss what you would like to change.

License

This project is licensed under the MIT License 

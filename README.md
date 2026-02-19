# Amazon Sentiment Analysis

Project Overview
This project implements sentiment analysis on Amazon product reviews using AWS Comprehend. It processes uploaded datasets like "DS products.csv" and "Amazon Reviews.csv" to classify sentiments as positive, negative, neutral, or mixed.

Features
Upload CSV files containing product reviews for batch analysis.

Visualize sentiment distributions via integrated charts.

Jupyter notebook support for exploratory data analysis and model evaluation.

Tech Stack
AWS Comprehend: Core NLP service for sentiment detection.

Python/Jupyter: Environment for data processing and visualization.

Libraries: Pandas, Matplotlib/Seaborn (inferred from typical setups).

Quick Start
Clone the repository and open in Jupyter.

Upload review CSV files via the interface.

Run the analysis notebook to detect sentiments and generate reports.
​

Files
File Name	Description
DS products.csv	Dataset of DS product reviews.
​
Amazon Reviews.csv	Amazon product reviews dataset.
​
README	Project documentation.
Usage
Load data in Jupyter, call AWS Comprehend API on review text columns, and aggregate results. Example: Batch process up to 25 reviews per API call for efficiency.

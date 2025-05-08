# FAKE-NEWS-DETECTION
Fake News Detection using NLP
Overview
This project implements a machine learning model to classify news articles as "real" or "fake" using two datasets: fake.csv (containing fake news articles) and true.csv (containing genuine news articles). The solution leverages Natural Language Processing (NLP) techniques to address the growing challenge of misinformation in digital media.
Project Structure
The notebook is organized into the following sections:

Libraries: Importing necessary Python libraries for data analysis, visualization, and machine learning.

Loading Dataset: Loading the datasets containing fake and true news articles.

Data Exploration: Initial exploration of the datasets to understand their structure and content.

Data Preprocessing: Cleaning and preparing the text data for analysis, including label assignment.

Model Training: Training machine learning models (Logistic Regression, Decision Tree, Random Forest) to classify news articles.

Evaluation: Assessing model performance using accuracy and classification reports.

Key Features
Data Loading: Uses Pandas to load and merge datasets of fake and true news.

Text Preprocessing: Includes text cleaning and feature extraction using TF-IDF (Term Frequency-Inverse Document Frequency).

Model Comparison: Evaluates multiple classifiers to determine the best-performing model.

Visualization: Uses Seaborn and Matplotlib for data visualization.

Requirements
To run this notebook, ensure you have the following libraries installed:

pandas

seaborn

matplotlib

scikit-learn

wordcloud

re (for text cleaning)

Usage
Clone the repository or download the notebook.

Install the required libraries using pip install -r requirements.txt (if a requirements file is provided).

Run the notebook cells sequentially to perform data loading, preprocessing, model training, and evaluation.

Dataset
The project uses two datasets:

Fake.csv: Contains fake news articles.

True.csv: Contains true news articles.

Each dataset includes columns such as title, text, subject, and date. A label column is added to distinguish between fake (0) and true (1) news.

Results
The notebook demonstrates the performance of different machine learning models in classifying news articles. Key metrics such as accuracy and classification reports are provided to compare model effectiveness.

Future Work
Experiment with more advanced models like BERT or GPT for better text understanding.

Incorporate additional features such as sentiment analysis or metadata.

Deploy the model as a web application for real-time fake news detection.

Author
[Prince Singh]


License
This project is licensed under the MIT License. See the LICENSE file for details.

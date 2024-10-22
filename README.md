# Zomato Review Sentiment Analysis

## Project Description:

This repository implements a sentiment analysis model to classify Zomato reviews as positive or negative. It utilizes the Naive Bayes algorithm and includes data preprocessing, feature extraction, model training, and evaluation.

## Features:

- Data Preprocessing: Cleans review text by removing special characters, converting to lowercase, and splitting into words. Removes stopwords and performs stemming.
- Feature Extraction: Uses CountVectorizer to convert text reviews into numerical features based on word frequency.
- Model Training and Evaluation: Splits the data into training and testing sets, trains a Naive Bayes classifier, and evaluates its performance using accuracy score and confusion matrix.
- Visualization: Visualizes the top 20 most frequent words and confusion matrix for better understanding of the results.

## Requirements:

* Python 3.x
* Libraries: numpy, pandas, matplotlib, nltk, sklearn, seaborn

## How to Use:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ar-archith/Zomato_Review_Analysis.git
2. **Install Libraries:**
   ```bash
   pip install numpy pandas matplotlib nltk sklearn seaborn
3. **Run the Notebook:**
   Open the `Zomato_Review_Analysis.ipynb` file in your preferred Jupyter Notebook environment and execute the code cells.

## Dataset:

The script assumes a CSV file named `Zomato_Review_Kaggle.csv` exists in the same directory. This file should contain user reviews and their corresponding sentiment labels.

## Note:

This project provides a basic implementation of sentiment analysis. You can explore other algorithms, feature extraction techniques, and evaluation metrics to further enhance the model's performance.

Feel free to explore the code, modify it, and adapt it for your specific sentiment analysis tasks!

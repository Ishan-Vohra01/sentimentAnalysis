# Sentiment Analysis on Amazon Alexa Reviews

## Overview
This project performs **sentiment analysis** on the **Amazon Alexa Reviews dataset**. The dataset contains customer reviews and their associated sentiments (positive/negative). The analysis involves text preprocessing, feature extraction, and applying machine learning models to classify sentiments.

## Dataset
The dataset is sourced from Kaggle: [Amazon Alexa Reviews](https://www.kaggle.com/datasets/mahmoudshaheen1134/amazon-alexa-reviews-dataset)

## Features Used
- **verified_reviews**: Text reviews by customers.
- **length**: Length of the review.
- **sentiment**: Label indicating positive or negative sentiment.

## Project Workflow
1. **Data Preprocessing**:
   - Handling missing values.
   - Tokenization and stopword removal using `nltk`.
   - Creating new features like text length.

2. **Feature Extraction**:
   - Using **CountVectorizer** to convert text into numerical features.
   - Scaling numerical data with **MinMaxScaler**.

3. **Model Training & Evaluation**:
   - Applying **Random Forest Classifier** and **XGBoost** for sentiment classification.
   - Performing cross-validation for performance assessment.

## Dependencies
The following Python libraries are used:
```bash
pip install opendatasets pandas numpy seaborn matplotlib nltk scikit-learn
```

## Running the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/Ishan-Vohra01/sentiment-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sentiment-analysis
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook Senitment.ipynb
   ```

## Results
- Sentiment classification is performed using machine learning models.
- The performance is evaluated using metrics such as accuracy and F1-score.
- Visualizations provide insights into review distributions and sentiment trends.


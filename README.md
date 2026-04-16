# **Sentiment Analysis for English Center Reviews in Vietnam**

### **INTRODUCTION**
This project focuses on applying Machine Learning models to perform sentiment analysis on feedback from students and parents. The goal is to evalute the quality of education at English language centers in Vietnam. It implements the entire process, from data collection and preprocessing to model training, performance comparison and selecting the most suitable model.
### **MODELS USED FOR TRAINING IN THIS PROJECT**
- `Naive Bayes:` A probabilistic classification algorithm that predicts data categories based on likelihood.
- `Logistic Regression:` A statistical model for binary classification that uses the sigmoid function to estimate class probabilities.
- `Random Forest:` An ensemble learning method that combines multiple decision trees using bootstrapping to improve classification accuracy.
- `LSTM:` An RNN architecture that captures long-term dependencies and mitigates the vanishing gradient problem.
### **WORKFLOW**
- `Data Collection:` Using web crawling to collect data from Google Maps.
- `Data Preprocessing:` Text cleaning, lowercasing, removing special characters, tokenizing and labeling.
- `Feature Engineering:` Converting text into numerical vectors using TF-IDF and Word2Vec.
- `Training and Evaluation:` Data splitting and performance measurement using Confusion Matrix and Accuracy/F1-scores.
### **TECHNOLOGIES**
- Python
- Scikit-learn
- Keras
- TF-IDF
- Word2Vec
- Playwright
- BeautifulSoup
- LSTM

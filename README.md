# Chat Sentiment Analysis

This project aims to perform sentiment analysis on chat messages using machine learning techniques. The dataset used for this analysis is the "Chat Sentiment Dataset" obtained from Kaggle.

🔗 Dataset Source: [Chat Sentiment Dataset](https://www.kaggle.com/datasets/nursyahrina/chat-sentiment-dataset)

## Project Overview

The goal of this project is to develop a sentiment analysis machine learning model that can classify chat messages into three sentiment classes: positive, negative, and neutral. The dataset consists of chat messages that contain various elements such as text, special characters, numbers, emoji/emoticons, and URL addresses. The project involves the following steps:

1. **Dataset Exploration**: Analyze the structure and content of the dataset, and gain insights into the distribution of sentiment classes.

2. **Data Preprocessing**: Clean and preprocess the chat messages by removing URLs, special characters, and numbers. Convert the text to lowercase and remove extra whitespaces.

3. **Feature Extraction**: Transform the preprocessed text data into numerical features using techniques such as TF-IDF or word embeddings.

4. **Model Training**: Train a machine learning model, such as a Support Vector Machine (SVM) or a neural network, using the preprocessed data and the extracted features.

5. **Model Evaluation**: Evaluate the performance of the trained model using appropriate evaluation metrics, such as accuracy, precision, recall, and F1-score.

6. **Sentiment Analysis**: Apply the trained model to classify new chat messages and predict their sentiment.

## Requirements

- Python 3.x
- Pandas
- Scikit-learn

## Usage

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
2. **Install the required dependencies**:
   ```bash
   pip install pandas scikit-learn
3. **Run the Jupyter Notebook or Python** script to execute the different steps of the project.
4. **Explore the results**, including the analysis of the dataset, the trained model's performance, and the sentiment analysis predictions on new chat messages.
![image](https://github.com/anushkapatil18/MessageSentiments/assets/72657551/8e1f4fb1-1c2a-4404-bbb5-81d8ad6e3e49)

## Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please submit a pull request.

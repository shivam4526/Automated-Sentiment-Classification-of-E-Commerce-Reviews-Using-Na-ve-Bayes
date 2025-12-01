
# **Sentiment Analysis of Flipkart Customer Reviews**

## **📌 Overview**

In today’s digital marketplace, customer opinions play a critical role in the success of e-commerce businesses. With the rapid growth of online shopping platforms such as **Flipkart**, customers increasingly rely on product reviews to make informed purchasing decisions. A single positive or negative review can significantly influence a product’s reputation and sales. However, due to the massive volume of reviews generated daily, manually analyzing customer feedback becomes impractical and time-consuming.

To overcome this challenge, businesses use **Sentiment Analysis**, a branch of text mining and machine learning that automatically classifies customer opinions into categories such as **Positive**, **Neutral**, and **Negative**. Sentiment analysis helps organizations monitor customer satisfaction, identify product issues, understand user perception, and make data-driven improvements in product quality and marketing strategies.

---

## **🎯 Project Objective**

This project implements a **Sentiment Classification System** using the **Naïve Bayes algorithm**, one of the most widely used supervised learning techniques for text analysis.
The objective is to:

* Process and analyze Flipkart customer reviews
* Classify them into **three sentiment categories**

  * 👍 Positive
  * 😐 Neutral
  * 👎 Negative
* Generate insights based on emotional patterns found in the text

The Naïve Bayes classifier works by evaluating word frequency and patterns in reviews to predict overall sentiment. It learns from historical review data and uses that knowledge to classify new, unseen reviews.

---

## **🛠️ Technologies & Libraries Used**

The project is implemented in **Python**, chosen for its strong ecosystem in data science and machine learning.

### **Key Libraries**

* **Pandas** – Data loading and manipulation
* **NLTK** – Text preprocessing and natural language processing
* **Scikit-Learn** – Machine learning model building and evaluation
* **Matplotlib & Seaborn** – Data visualization

### **Dataset**

* Flipkart product reviews in **CSV format**
* Includes review text and rating information
* Used for training and testing the Naïve Bayes sentiment model

---

## **📊 Model Evaluation**

The Naïve Bayes classifier predicts sentiment based on probability theory and word occurrence patterns.
Model performance is evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* **Visualizations** to understand classification results

---

## **📁 Project Structure**

```
|-- dataset/
|   |-- flipkart_reviews.csv
|
|-- notebooks/
|   |-- sentiment_analysis.ipynb
|
|-- src/
|   |-- preprocessing.py
|   |-- model.py
|
|-- README.md
```

---

## **🚀 Results & Insights**

The model effectively classifies Flipkart reviews into sentiment categories and provides insights useful for:

* Product improvement
* Customer satisfaction analysis
* Identifying common issues
* Understanding customer emotions

---



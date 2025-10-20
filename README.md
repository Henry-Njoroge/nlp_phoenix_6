# 🐦 Twitter Sentiment Analysis for Tech Brands

## 🧠 Overview
In today’s digital age, social media platforms like **Twitter (X)** have become powerful spaces where consumers freely express their opinions about brands, products, and user experiences.  

For technology giants like **Apple** and **Google**, tweets represent an unfiltered stream of public perception that can influence reputation, marketing strategies, and customer loyalty.  

The goal of this project is to **build an automated system** that analyzes and classifies sentiments expressed in tweets related to Apple and Google products.  
This helps organizations **understand market sentiment trends** and **react strategically** to consumer feedback.

---

## 📊 Data Understanding

The dataset contains **Twitter posts (tweets)** from the **SXSW conference**, each labeled with sentiment information.  
It has the following key columns:

| Column | Description |
|--------|--------------|
| `tweet_text` | The original tweet content mentioning tech products and SXSW experiences. |
| `emotion_in_tweet_is_directed_at` | The specific Apple or Google product mentioned. |
| `is_there_an_emotion_directed_at_a_brand_or_product` | The sentiment expressed — *positive, negative, or neutral.* |

The dataset captures real-world user experiences and opinions about **Apple** and **Google** products, including excitement, praise, frustration, and feedback shared during the SXSW tech conference.

---

## 👥 Stakeholders

The primary stakeholders for this project include:

### 🏢 Technology Companies (Apple & Google)
- Understand **public perception** and **sentiment trends** toward their products.  
- Use insights to make **data-driven decisions** on product improvements, marketing, and engagement strategies.

### 📈 Marketing Teams
- Gauge **brand reputation** and **consumer sentiment**.  
- Tailor marketing campaigns and **respond to feedback** effectively.

### 💬 Customer Service Teams
- Detect and address **negative feedback early**.  
- Improve **customer satisfaction** and **brand loyalty** through proactive engagement.

---

## 🤖 Modeling

We developed and evaluated several machine learning and deep learning models to classify tweet sentiments.  
Each model’s performance was measured using **Accuracy** and **F1-Macro** scores — with the **F1-Macro** score chosen as the main metric due to the **imbalanced sentiment classes**.

| Model | Description | Accuracy | F1-Macro Score |
|--------|--------------|-----------|----------------|
| **Multinomial Naive Bayes** | Baseline model for text classification | 0.48 | 0.42 |
| **Support Vector Machine (SVM)** | Linear model for text classification | 0.58 | 0.50 |
| **Random Forest Classifier** | Ensemble model using decision trees | 0.57 | 0.48 |
| **XGBoost Classifier** | Gradient boosting model | 0.56 | 0.47 |
| **Simple RNN** | Basic recurrent neural network | 0.576 | — |
| **LSTM** | Long Short-Term Memory network capturing long-term dependencies | **0.629** | — |

Among these, the **LSTM model** achieved the **best performance**, leveraging sequential patterns in text to better understand context and emotion.

---

## 🧾 Summary

This project demonstrates how natural language processing (NLP) and deep learning can be applied to real-world social media data to:
- Understand brand perception  
- Detect emotional trends  
- Support data-driven marketing and customer strategies  

The **LSTM model** proved most effective for this task, showing the potential of deep learning methods in sentiment analysis applications.

---

## 🧠 Authors

| Name | LinkedIn |
|------|-----------|
| **Jeff Kandie** | [linkedin.com/in/jeff-kandie](https://www.linkedin.com/in/jeff-kandie) |
| **Peris Kigo** | [linkedin.com/in/peris-kigo-098170302](https://www.linkedin.com/in/peris-kigo-098170302) |
| **Henry Njoroge** | [linkedin.com/in/henry-njoroge](https://www.linkedin.com/in/henry-njoroge/) |
| **Mary Kamithi** | [linkedin.com/in/marykamithi](http://www.linkedin.com/in/marykamithi) |
| **Sharlene Ateyo** | [linkedin.com/in/sharlene-ateyo-85a286229](http://www.linkedin.com/in/sharlene-ateyo-85a286229) |
| **Kelvin Kinoti** | [linkedin.com/in/kelvin-kinoti-782066210](https://www.linkedin.com/in/kelvin-kinoti-782066210/) |

---

⭐ *If you found this project insightful, consider starring the repository and connecting with us on LinkedIn!*

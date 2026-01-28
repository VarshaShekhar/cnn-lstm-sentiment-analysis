
# 🎬 CNN-LSTM Sentiment Analysis on IMDB Movie Reviews

🚀 A hands-on **Natural Language Processing (NLP)** project that implements and compares **LSTM** and **CNN + LSTM** deep learning models for **sentiment classification** of movie reviews.

This project demonstrates practical applications of **Deep Learning for Text**, including **text preprocessing, sequence modeling, hybrid architectures, model evaluation, and result comparison**.

---

![Project Thumbnail](cnn_lstm.png)

---
## 📌 Overview

* **Goal**: Classify IMDB movie reviews as **positive** or **negative**
* **Focus Areas**:

  * Text preprocessing and sequence padding
  * Word embeddings for textual representation
  * LSTM-based sentiment classification
  * Hybrid CNN + LSTM architecture
  * Model evaluation using Accuracy and F1-score
  * Comparative analysis of models
* **Framework Used**: TensorFlow + Keras
* **Evaluation Metrics**: Accuracy, F1 Score

---

## 🧠 Problem Statement

Movie reviews are written in natural language and vary in length and structure.
The task is to **automatically determine the sentiment** (positive or negative) of a given review.

This problem is a classic **binary text classification task**, widely used to evaluate NLP models and deep learning architectures.

---

## 📊 Dataset

* **IMDB Movie Review Dataset**
* 25,000 training samples and 25,000 test samples
* Binary sentiment labels:

  * `0` → Negative
  * `1` → Positive
* Dataset provided directly by **Keras**

---

## 🛠️ Technologies Used

* Python 🐍
* NumPy 📊
* TensorFlow & Keras 🧠
* scikit-learn ⚙️
* Jupyter Notebook 📓

---

## ✨ Key Features

* 📝 **Text Preprocessing**: Tokenized and padded review sequences
* 🔢 **Word Embeddings**: Dense vector representation of words
* 🔁 **LSTM Model**: Captures sequential and contextual dependencies in text
* 🧩 **CNN + LSTM Model**:

  * CNN extracts local n-gram features
  * LSTM captures long-term dependencies
* 🧮 **Evaluation Metrics**: Accuracy and F1 score
* 🔍 **Prediction Analysis**: Displays predictions for random test samples
* 📐 **Architecture Diagrams**: Visual explanation of model structures

---

## 🧩 Project Structure

### 🔹 LSTM Model

* **Purpose**: Learn sentiment from sequential word dependencies
* **Architecture**:

```
Input → Embedding → LSTM → Dense (Sigmoid)
```

* Serves as the **baseline model** for comparison.

---

### 🔹 CNN + LSTM Model

* **Purpose**: Combine local feature extraction with sequence modeling
* **Architecture**:

```
Input → Embedding → Conv1D → MaxPooling → LSTM → Dense (Sigmoid)
```

* CNN captures local word patterns (n-grams)
* LSTM captures contextual and temporal information

---

### 🔹 Training & Evaluation

* Models trained on IMDB training data
* Evaluated on unseen test data
* Metrics used:

  * **Accuracy**
  * **F1 Score**
* Same test samples are used to compare predictions across both models

---

## 📈 Results Summary

| Model      | Accuracy | F1 Score |
| ---------- | -------- | -------- |
| LSTM       | High     | High     |
| CNN + LSTM | High     | High     |

> *Exact values may vary slightly depending on training configuration and random initialization.*

---

## 📁 Files

* `CNN_LSTM_Text_Classification_IMDB.ipynb` – Complete notebook with:

  * Data preprocessing
  * Model implementation
  * Training and evaluation
  * Predictions and comparison
* `images/` – Architecture diagrams for LSTM and CNN + LSTM models

---

## 🧾 Notes

* Training time may vary depending on CPU/GPU availability
* Some FutureWarnings from Keras/NumPy may appear and can be safely ignored
* This project is intended for **learning and demonstration purposes**

---

## 🤝 Connect

- [LinkedIn](https://www.linkedin.com/in/varsha-shekhar)
- [Gmail](varshaiyer96@gmail.com)

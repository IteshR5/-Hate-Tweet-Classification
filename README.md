# 🧠 Hate Tweet Classification using ML and Deep Embeddings

This project tackles the problem of detecting hate speech in tweets using various text embedding techniques and machine learning models. It compares traditional NLP feature extraction methods like Bag-of-Words and TF-IDF with deep learning models such as BERT and the Universal Sentence Encoder.

---

## 🧠 Problem Description

The rise of hate speech on social media platforms poses significant risks to user safety, mental health, and societal harmony. Manual moderation is inefficient due to the scale of user-generated content. Hence, automated hate speech detection systems are essential.

**Challenges:**
- Diverse linguistic styles and slang in tweets
- Ambiguity and sarcasm
- High class imbalance between hate and non-hate content

---

## 💡 Solution Provided

This project presents a comparative analysis of multiple text representation techniques applied to tweet classification:

- **Preprocessing**: Cleansing tweets (removing links, mentions, numbers, punctuation, stopwords)
- **Text Embeddings**:
  - Bag-of-Words
  - TF-IDF
  - BERT (DistilBERT)
  - Universal Sentence Encoder (USE)
- **Classification Model**: Logistic Regression
- **Evaluation Metrics**: Accuracy, Classification Report, Confusion Matrix

The goal is to identify the most effective embedding method for detecting hate speech.

---

## 🏭 Industry Impact

Automated hate speech detection can be applied in:
- 🐦 **Social Media Platforms** – Real-time moderation of harmful content
- 🧑‍⚖️ **Legal Tech** – Evidence extraction for online harassment
- 🔐 **Cybersecurity** – Identifying threats and abuse in open forums
- 💬 **Customer Support** – Filtering abusive language in chatbot systems

---

## ✨ Key Features

- 🧹 Text cleaning: Lowercasing, lemmatization, stopword removal
- 🔠 Comparative vectorization: BoW, TF-IDF, BERT, USE
- 🤖 Model training with Logistic Regression
- 📊 Performance evaluation using accuracy and classification metrics
- 📈 Visualization of embedding-based model performance

---
## Contributing
Contributions are welcome! To contribute:

1. Fork the repository.

2. Create a new branch:
   
  ```
  git checkout -b feature/your-feature-name
  ```

3. Make your changes and commit them:

  ```
  git commit -m 'Add your feature description'
  ```

4. Push to the branch:
  
  ```
  git push origin feature/your-feature-name
  ```

5. Open a pull request with a description of your changes.
   
**Thank you for choosing this project. Hoping that this project proves useful and delivers a seamless experience for your needs!**

## 🔧 Tools & Libraries Used

- `pandas`, `numpy` – Data handling
- `sklearn` – Model training and evaluation
- `nltk` – Text preprocessing and lemmatization
- `tensorflow_hub` – Universal Sentence Encoder
- `transformers` – BERT & DistilBERT embeddings
- `matplotlib` – Visualization
- `re` – Regex for text cleaning

---




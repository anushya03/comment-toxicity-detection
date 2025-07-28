# 🧠 Comment Toxicity Detection using NLP and Machine Learning

This project focuses on building an intelligent **Comment Toxicity Detection System** that classifies user comments as `toxic`, `severe toxic`, `obscene`, `threat`, `insult`, or `identity hate`. It uses Natural Language Processing (NLP) and Machine Learning (ML) to help moderate and maintain healthy online platforms.

![toxicity-prediction-demo](demo/demo_video.gif) <!-- Optional GIF or image preview -->

## 📌 Demo

🎥 Watch the full demo here: [Click to Watch](https://www.linkedin.com/in/anushyavarshinik/)  

---

## 🚀 Features

- Multi-label classification (one comment can have multiple toxic traits)
- Real-world dataset from Kaggle's Jigsaw challenge
- Text preprocessing, vectorization, and classification
- Real-time prediction interface
- Ready to deploy with Streamlit or Flask

---

## 📂 Dataset

- **Source:** [Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data)
- Contains ~160,000 labeled comments
- Labels:
  - `toxic`
  - `severe_toxic`
  - `obscene`
  - `threat`
  - `insult`
  - `identity_hate`

---

## ⚙️ Tech Stack

| Task                  | Tools / Libraries                      |
|-----------------------|----------------------------------------|
| Language              | Python                                 |
| NLP                   | NLTK, RegEx, stopwords                 |
| Feature Engineering   | TF-IDF                                 |
| Modeling              | Logistic Regression, LSTM              |
| Evaluation            | Accuracy, F1-Score, Confusion Matrix   |
| Visualization         | Matplotlib, Seaborn                    |

---

## 🛠 How to Run the Project Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/comment-toxicity-detector.git
   cd comment-toxicity-detector

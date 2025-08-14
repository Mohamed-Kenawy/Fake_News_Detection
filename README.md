# Fake News Detection 📰❌✅

## 📌 Overview

This project focuses on detecting fake news articles using Natural Language Processing (NLP) and machine learning techniques. It classifies news articles as real or fake based on their textual content.
## 📂 Dataset
The project uses:
- **Fake.csv** → Fake news articles
- **True.csv** → Real news articles
- Data link: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset?select=Fake.csv

## Preprocessing Steps:
- Merge datasets and assign labels (`0` = fake, `1` = real)
- Drop unnecessary columns: `date`, `subject`
- Remove special characters and numbers
- Lowercase text
- Tokenize, remove stopwords, and lemmatize words
- Combine `title` and `text` into a single `content` column

## Visualization:
- **WordCloud** visualization for most frequent words

##  Model Used
- **Support Vector Machine (SVM)** 

## Feature Extraction:
- **TF-IDF Vectorization** 

##  Evaluation Metrics
- **Accuracy Score**
- **F1-Score**
- **Classification Report**
- **Confusion Matrix**


## 🔮 Example Results 
| Model                | Accuracy | F1-Score |
|----------------------|----------|----------|
| SVM                  | 0.99    | 0.99   |

## 📥 Clone Repository
```bash
git clone https://github.com/Mohamed-Kenawy/Fake_News_Detection.git
cd Fake_News_Detection




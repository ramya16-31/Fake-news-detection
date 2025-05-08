# 📰 Advanced Fake News Detection Using NLP

This project is focused on detecting fake news articles using advanced Natural Language Processing (NLP) techniques. The model analyzes the content, author, source, and publication metadata to predict whether a given news article is real or fake.

## 🚀 Project Features

- Multifeature dataset (text, title, author, source, date)
- NLP preprocessing (tokenization, stemming, TF-IDF, etc.)
- Classification models (Logistic Regression, Random Forest, etc.)
- Model evaluation (accuracy, confusion matrix, ROC-AUC)
- Web app interface using Flask (optional)
- Extendable for real-world datasets

---

## 📁 Dataset

The dataset is located in `advanced_fake_news_dataset.csv` and contains:

| Column   | Description                               |
|----------|-------------------------------------------|
| `id`     | Unique identifier                         |
| `title`  | Headline of the news                      |
| `text`   | Full news article content                 |
| `author` | Article author name                       |
| `source` | News publisher domain                     |
| `date`   | Publication date                          |
| `label`  | 1 = Real, 0 = Fake                         |

---

## 🛠️ Installation

```bash
git clone https://github.com/your-username/fake-news-detection-nlp.git
cd fake-news-detection-nlp
pip install -r requirements.txt
**
 ##Project Structure

├── app.py                  # Flask backend
├── templates/
│   └── index.html          # Frontend HTML template
├── static/
│   └── style.css           # Custom styling
├── model/
│   ├── tfidf_vectorizer.pkl
│   └── fake_news_model.pkl
├── dataset/
│   └── fake_or_real_news.csv
├── README.md
└── requirements.txt


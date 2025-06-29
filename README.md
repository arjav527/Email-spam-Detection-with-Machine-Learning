# 📱 SMS Spam Detection using Machine Learning

This project demonstrates a complete pipeline to detect spam SMS messages using Natural Language Processing (NLP) and a Naive Bayes classifier. It includes data cleaning, preprocessing, feature extraction with TF-IDF, model training, evaluation, and visualizations.

---

## 📂 Dataset

- **Source:** [UCI SMS Spam Dataset / Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Total Rows:** 5572
- **Columns:**
  - `label`: "ham" (non-spam) or "spam"
  - `message`: SMS text content

---

## 🛠️ Tools & Libraries Used

- `Python`
- `Pandas`, `NumPy` – Data handling
- `Matplotlib`, `Seaborn` – Visualization
- `scikit-learn` – Machine Learning
- `TF-IDF Vectorizer` – Feature Extraction
- `MultinomialNB` – Classification Model

---

## 🚀 Workflow

### 1. **Load Data**
- Read the CSV and inspect structure

### 2. **Clean & Analyze**
- Remove nulls
- Add text length feature
- Visualize class distribution

### 3. **Text Preprocessing**
- Lowercase, remove punctuation, numbers
- Strip extra whitespaces

### 4. **Feature Extraction**
- Use **TF-IDF Vectorizer** with max 3000 features

### 5. **Train-Test Split**
- 80% training, 20% testing

### 6. **Model Training**
- **Multinomial Naive Bayes**

### 7. **Model Evaluation**
- Accuracy
- Confusion Matrix
- Classification Report

### 8. **Visualizations**
- Spam vs Ham pie chart
- WordClouds
- Most frequent spam/ham words
- Confusion matrix heatmap

---

## ✅ Results

- **Accuracy:** ~97–99%
- **High Precision and Recall** for spam detection
- Excellent generalization on unseen data

---

## 🔮 Future Improvements

- Try models like Logistic Regression, SVM, XGBoost
- Use more complex NLP (Lemmatization, Named Entity Recognition)
- Build a **web app** (Flask or Streamlit)
- Live deployment with continuous learning

---

## 📌 Screenshots

| Spam vs Ham Pie Chart | WordClouds | Confusion Matrix |
|-----------------------|------------|------------------|
| ![pie](./screenshots/pie.png) | ![wordcloud](./screenshots/wordcloud.png) | ![cmatrix](./screenshots/cm.png) |

---

## 🧠 Author

**Arjav Jain**  
📧 arjavjain062@gmail.com  
📌 BCA Student, Teerthanker Mahaveer University  
🌐 GitHub: [@arjav527](https://github.com/arjav527)

---

## ⭐ Give this project a star if you like it!



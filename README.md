# 📰 Fake News Detection using Machine Learning

This project uses Natural Language Processing (NLP) and Logistic Regression to classify whether a news article is **FAKE** or **REAL**.

---

## 📂 Dataset

- Dataset used: [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- Contains: `Fake.csv`, `True.csv`

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib
- TfidfVectorizer
- LogisticRegression

---

## 📊 Features

- Merges real and fake news data
- Cleans and preprocesses the text
- Splits data into training & testing
- Trains logistic regression model
- Evaluates performance using accuracy, precision, recall, and F1-score
- Visualizations:
  - Label distribution pie chart
  - Word count histogram
  - Confusion matrix
  - Performance bar chart

---

## 🧠 Model Accuracy

Achieved around **93%** accuracy on test data.

---

## 📷 Sample Output

![Confusion Matrix](https://via.placeholder.com/600x400.png?text=Add+your+plot+here+if+needed)

---

## 🧪 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
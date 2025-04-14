# 🎓 College Events Analyzer

A console-based machine learning project in Python that analyzes college event data to predict feedback sentiment and estimate participant turnout. Built using only basic Python libraries — no external NLP or web frameworks.

---

## 🧠 Project Features

✅ Analyze real college event data
✅ Predict feedback sentiment (Positive / Neutral / Negative)
✅ Predict number of participants based on event type, budget, and department
✅ No use of NLTK, TextBlob, or Streamlit — pure Python + scikit-learn
✅ Easy to run in any terminal or IDE

---

## 📊 Dataset Overview

The dataset contains 20 college events with the following details:

| Column            | Description                            |
|------------------|----------------------------------------|
| `Event_Name`      | Name of the event                     |
| `Department`      | Organizing department (CSE, ECE, etc.)|
| `Event_Type`      | Technical, Cultural, Sports, etc.     |
| `Date`            | Date of the event                     |
| `Budget`          | Budget allocated for the event        |
| `Participants`    | Number of attendees                   |
| `Feedback`        | Text review by students               |
| `Sentiment_Label` | (Manual) 1 = Positive, 0 = Neutral, -1 = Negative |

---

## ⚙️ Technologies Used

- **Python**
- **Pandas**
- **Scikit-learn** (TF-IDF, Logistic Regression, Label Encoding)

---

## 🖥️ How to Run

1. Clone this repository or download the ZIP
2. Ensure you have Python installed (3.8+ recommended)
3. Install dependencies:
   ```bash
   pip install pandas scikit-learn

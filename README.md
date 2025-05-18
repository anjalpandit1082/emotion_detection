# Emotion Detection from Text 🧠💬

This project detects **emotions from textual input** using machine learning techniques. Given a sentence, it classifies the emotion into categories like `Happy`, `Sad`, `Angry`, `Fear`, `Love`, or `Surprise`.

---

## 📌 Features

- Text preprocessing (cleaning, lowercasing, stopword removal)
- TF-IDF vectorization
- Model training using **Logistic Regression**
- Emotion prediction for custom text input
- Accuracy evaluation and classification report

---

## 🧪 Technologies Used

- Python 🐍
- Pandas & NumPy
- Scikit-learn (Machine Learning)
- Google Colab
- Jupyter Notebook (`.ipynb`)

---

## 💡 How It Works

1. **Data Loading** – Emotion-labeled sentences are loaded.
2. **Text Preprocessing** – Noise like punctuation & stopwords are removed.
3. **Feature Extraction** – Text is converted into numerical form using TF-IDF.
4. **Model Training** – Logistic Regression is trained on the labeled data.
5. **Prediction** – User inputs are passed through the model for emotion classification.

---

## 🎯 Example

```text
Input: "I am feeling so excited today!"
Output: Happy

Input: "I miss you."
Output: Sad

You can upload your own text data and try the model for emotion prediction.

Requirements
Python 3.x

Libraries: numpy, pandas, scikit-learn, matplotlib, seaborn, nltk (You can install these using pip in Colab)

File Description
emotion_detection_colab.ipynb — Main notebook with complete code and explanations.

Author
Anjali Kumari
Student at Guru Gobind Singh Educational Society Technical Campus
Project: Google Meet Automation & Emotion Detection

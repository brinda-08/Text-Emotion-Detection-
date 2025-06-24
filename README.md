# Text Emotion Detection

A machine learning model to detect emotions from text.

## 📁 Dataset Used
- emotion_dataset_raw.csv: Contains labeled text data with emotions.

## ⚙ Approach Summary
- Used CountVectorizer for feature extraction.
- Trained models: Random Forest, SVM.
- Final model: SVM pipeline saved as text_emotion.pkl.
- Built a frontend using Streamlit in app.py.

## 📦 Dependencies
- pandas
- numpy
- sklearn
- streamlit
- joblib
- altair

## 🧪 How to Run
```bash
streamlit run app.py

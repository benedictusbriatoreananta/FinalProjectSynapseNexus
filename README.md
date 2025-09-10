# 🧠 Cyberbullying Tweet Classifier

**Final Project – Kelompok 5, Digital Skola Data Science Batch 48**  

A machine learning project to classify tweets into various categories of cyberbullying using **Support Vector Machine (LinearSVC)** with **TF-IDF** representation.

---

## 📂 Project Files

| File                          | Description                                            |
|-------------------------------|--------------------------------------------------------|
| `cyberbullying_tweets.csv`    | Original dataset                                       |
| `ProjectFinal_klp5.ipynb`     | Jupyter Notebook: EDA, preprocessing, modeling, tuning |
| `best_svm_model.pkl`          | Best model (SVM after tuning)                          |
| `tfidf_vectorizer.pkl`        | Trained TF-IDF vectorizer                              |
| `label_encoder.pkl`           | Label encoder for target classes                       |
| `streamlit_app.py`            | Streamlit web application for prediction               |
| `README.md`                   | Documentation                                          |
| `slides_kelompok5.pptx`       | (Optional) Presentation slides                         |

---

## 🏆 Best Model
- **Algorithm**: SVM (LinearSVC)  
- **Hyperparameter**: `C=0.1`  
- **Test Accuracy**: **83.64%**  
- Robust to unseen/unknown inputs  

---

## 🌐 Streamlit Web App
- Run the app:
  ```bash
  streamlit run streamlit_app.py

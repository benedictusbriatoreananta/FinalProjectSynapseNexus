# 🧠 Cyberbullying Tweet Classifier

**Final Project – Kelompok 5, Digital Skola Data Science Batch 48**

A machine learning project to classify tweets into various categories of cyberbullying using **Support Vector Machine (LinearSVC)** with **TF-IDF** representation.

---

## 📂 Project Files

| File                          | Description                                            |
| ----------------------------- | ------------------------------------------------------ |
| `cyberbullying_tweets.csv`    | Original dataset                                       |
| `ProjectFinal.ipynb`          | Jupyter Notebook: EDA, preprocessing, modeling, tuning |
| `requirements.txt`            | Dependencies for running the project                   |
| `streamlit_app.py`            | Streamlit web application for prediction               |
| `Input Word di Streamlit.txt` | Example input cases for testing the app                |
| `README.md`                   | Documentation                                          |

> ⚠️ **Note:** Model artifacts (`best_svm_model.pkl`, `tfidf_vectorizer.pkl`, `label_encoder.pkl`) are not included in this repository to keep it lightweight.  
> You can retrain the model using the notebook `ProjectFinal.ipynb`.

---

## 🏆 Best Model

- **Algorithm**: SVM (LinearSVC)
- **Hyperparameter**: `C=0.1`
- **Test Accuracy**: **83.64%**
- Robust to unseen/unknown inputs

---

## 🌐 Streamlit Web App

Run the app locally:

```bash
streamlit run streamlit_app.py
```

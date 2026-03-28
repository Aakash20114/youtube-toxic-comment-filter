# 🧠 YouTube Toxic Comment Filter

A Chrome Extension that detects and hides toxic comments on YouTube using Machine Learning.

---

## 🚀 Demo

🔴 Toxic Comment:
> "you are stupid"  
➡️ 🚫 Toxic Comment Hidden  

🟢 Normal Comment:
> "nice video"  
➡️ Visible  

---

## 🧩 Project Architecture

YouTube → Chrome Extension → Flask API → ML Model → Prediction → Hide Comment

---

## 🧠 Technologies Used

- Python (Flask)
- Machine Learning (Logistic Regression)
- TF-IDF (Text Feature Extraction)
- JavaScript (Chrome Extension)
- HTML & CSS

---

youtube-toxic-comment-filter/
│
├── backend/
│ ├── app.py
│ ├── toxicity_model.pkl
│ ├── tfidf_vectorizer.pkl
│
├── extension/
│ ├── manifest.json
│ ├── content.js
│ ├── popup.html
│ ├── popup.js
│ ├── style.css
│
├── notebook/
│ ├── toxicity_model.ipynb
│
├── README.md
├── requirements.txt


---

## ⚙️ How to Run

### 🔹 1. Start Backend
cd backend
python app.py


---

### 🔹 2. Load Chrome Extension

1. Open Chrome  
2. Go to `chrome://extensions/`  
3. Enable Developer Mode  
4. Click **Load Unpacked**  
5. Select `extension/` folder  

---

### 🔹 3. Open YouTube

- Open any video  
- Scroll comments  
- Toxic comments will be hidden automatically  

---

## 📊 Dataset

- Jigsaw Toxic Comment Classification Dataset (Kaggle)

---

## 🎯 Features

- Real-time toxicity detection  
- Automatic comment filtering  
- Lightweight ML model  
- Chrome Extension integration  

---

## 🧠 Machine Learning Model

- Logistic Regression  
- TF-IDF Vectorization  
- Binary Classification (Toxic / Non-Toxic)  

---

## ⚠️ Limitations

- Depends on dataset quality  
- May not detect sarcasm  
- Requires backend to be running  

---

## 👨‍💻 Author

**Aakash**

---

## ⭐ Future Improvements

- Add toxicity score  
- Highlight toxic words  
- Improve UI  
- Use deep learning models (BERT)

---

## ⭐ If you like this project, give it a star!
---



## 📂 Project Structure

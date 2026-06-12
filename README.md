# 🎭 <span style="color:darkred">Emotion Classification Using Machine Learning</span>

## 🌟 <span style="color:darkblue">Project Overview</span>
This project focuses on building an **Emotion Classification system** using **Natural Language Processing (NLP)** and **Machine Learning techniques**.  
The objective is to classify textual data into different emotion categories by applying preprocessing techniques, extracting meaningful features, training classification models, and evaluating their performance.

---

## 🎯 <span style="color:darkgreen">Objectives</span>
- 📂 Load and explore the given emotion dataset  
- 🧹 Perform text preprocessing and cleaning  
- 🔢 Convert textual data into numerical representations using **TF-IDF**  
- 🤖 Train and compare multiple machine learning models  
- 📊 Evaluate model performance using standard classification metrics  

---

## 📑 <span style="color:purple">Dataset</span>
The dataset consists of textual samples along with their corresponding **emotion labels**.  
The text data was processed and transformed into a suitable format for machine learning tasks.

---

## 🛠️ <span style="color:teal">Methodology</span>

### 1️⃣ Text Preprocessing
- 🔡 Conversion of text to lowercase  
- 🌐 Removal of URLs and HTML tags  
- ✂️ Removal of punctuation and numerical values  
- ⚪ Elimination of extra whitespaces  
- 📝 Tokenization of text into individual words  
- 🚫 Removal of stopwords to reduce noise  

➡️ These steps improve data quality, reduce vocabulary size, and enhance model performance.

---

### 2️⃣ Feature Extraction
- 📈 **TF-IDF (Term Frequency–Inverse Document Frequency)** Vectorization  
- Assigns higher importance to informative words while reducing the influence of common terms.

---

### 3️⃣ Model Development
- 🟡 **Naïve Bayes**  
  - Probabilistic classifier based on Bayes' Theorem  
  - Efficient on sparse text data, strong baseline model  

- 🔵 **Support Vector Machine (SVM)**  
  - Identifies the optimal decision boundary between classes  
  - Effective for high-dimensional text classification problems  

---

### 4️⃣ Model Evaluation
Models were evaluated using:  
- ✅ Accuracy Score  
- 📊 Weighted F1-Score  
- 📋 Classification Report  
- 🧩 Confusion Matrix  

---

## 🧰 <span style="color:orange">Tools and Libraries Used</span>
- 🐍 Python 3  
- 📓 Jupyter Notebook  
- 🐼 Pandas  
- 🔢 NumPy  
- 📚 NLTK  
- ⚙️ Scikit-learn  
- 🔎 Regular Expressions (re)  
## 📂 <span style="color:darkmagenta">Project Structure</span>
├── SENTIMENT_ANALYSIS.ipynb

├── nlp_dataset.csv

├── preprocessed_nlp_dataset.csv

├── README.txt

└── Output Results



---

## 🏁 <span style="color:darkred">Conclusion</span>
This project demonstrates the **complete workflow** of an NLP-based emotion classification pipeline.  
By combining preprocessing techniques, **TF-IDF feature extraction**, and machine learning algorithms such as **Naïve Bayes** and **SVM**, the system effectively classifies emotions from textual data.  

📌 The comparative evaluation provides insights into the strengths and limitations of each model and highlights the suitability of traditional ML approaches for emotion classification tasks.

---

👩‍💻 **Submitted by:**  
<span style="color:navy; font-weight:bold">Muhsina Safeeth</span>  
*Natural Language Processing Assignment*

---

## 📂 <span style="color:darkmagenta">Project Structure</span>

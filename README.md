# 📧 Spam Classifier - Machine Learning Project

A Machine Learning project that classifies messages as **Spam** or **Not Spam** using Natural Language Processing and a supervised ML algorithm. The final model is deployed as a **website** using Python (built in PyCharm).

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Natural Language Toolkit (NLTK)
- Streamlit or Flask (for web app)
- PyCharm (for development)

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning
- Removed unwanted columns, null values, and duplicates.
- Converted labels (`ham`, `spam`) to binary format.
- Preprocessed text: lowercasing, punctuation removal, stopword removal, stemming.

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualized word frequency in spam vs non-spam messages.
- Compared message lengths, word clouds.
- Analyzed data balance (ham vs spam).

### 3️⃣ Model Training
- Vectorized text using **TF-IDF**.
- Trained a **Multinomial Naive Bayes** classifier.
- Evaluated with accuracy, precision, recall, and confusion matrix.

### 4️⃣ Deployment
- Saved the model using `pickle`.
- Built a **web interface** to input messages and show predictions.

### 5️⃣ Website (Built in PyCharm)
- Created an interactive website using **Streamlit** or **Flask**.
- User can enter a message and see if it's classified as Spam or Not Spam.
- All development and deployment handled in **PyCharm** IDE.

---

## 📁 Folder Structure


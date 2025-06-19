# Email/SMS Spam Classifier

This project is a machine learning-based web application that classifies text messages as **Spam** or **Not Spam** using natural language processing (NLP) techniques and a trained **Multinomial Naive Bayes** model.

## 📊 Model Performance
- **Accuracy:** 98%
- **Precision:** 99%

## 🔍 Overview
The application takes a text message (email or SMS) as input and uses NLP techniques to clean and process the text. It then vectorizes the message using a **TF-IDF vectorizer** and classifies it using a trained model. The interface is built with **Streamlit**, allowing real-time message classification in a simple web app format.

## ⚙️ Technologies Used
- Python
- Scikit-learn
- NLTK
- Streamlit
- Pandas, NumPy

## 🧠 How It Works
1. **Text Preprocessing:** Lowercasing, tokenization, stopword removal, punctuation removal, and stemming.
2. **Vectorization:** Converts cleaned text into numerical features using TF-IDF.
3. **Model Prediction:** Uses a trained Multinomial Naive Bayes model to classify the message.
4. **Result Display:** Shows whether the message is spam or not in the Streamlit interface.

## 🖥️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/sms-spam-classifier.git
cd sms-spam-classifier
```
2. Create and Activate a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate  # For Windows
# OR
source venv/bin/activate  # For macOS/Linux
```

3. Install Dependencies
```bash
pip install -r requirements.txt
```
4. Run the App
```bash
streamlit run app.py
```


👩‍💻 Author
Qudsiya Siddique
Student | AIML Enthusiast | Web Developer
K. J. Somaiya Institute of Technology

##DEMO VIDEO
A demo video is attached in this

# SMS Spam Classifier

A Machine Learning based web application that classifies SMS messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) techniques and the Multinomial Naive Bayes algorithm.

## 🚀 Features

* Detects spam and non-spam SMS messages
* Text preprocessing using NLP
* TF-IDF Vectorization
* Machine Learning based classification
* Interactive Streamlit web interface
* Fast and accurate predictions

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Streamlit
* Matplotlib
* Seaborn

## 📊 Machine Learning Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Text Preprocessing

   * Lowercasing
   * Tokenization
   * Stopword Removal
   * Punctuation Removal
   * Stemming
4. Feature Extraction using TF-IDF
5. Model Training using Multinomial Naive Bayes
6. Model Evaluation
7. Web Application Deployment

## 📁 Project Structure

```
SMS-Spam-Classifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── spam.csv
├── sms-spam-classifier.ipynb
└── README.md
```

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/sms-spam-classifier.git
```

Navigate to the project directory:

```bash
cd sms-spam-classifier
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## 📷 Example

Input:

```
Congratulations! You have won a free iPhone.
```

Output:

```
Spam
```

Input:

```
Hey, are we still meeting at 5 PM today?
```

Output:

```
Not Spam
```

## 📈 Model Performance

The model uses TF-IDF vectorization and Multinomial Naive Bayes for text classification, achieving high accuracy and precision on the SMS Spam Collection dataset.

## 📌 Future Improvements

* Email spam detection
* Deep learning models
* Multi-language support
* Enhanced UI/UX
* Real-time message analysis

## 👨‍💻 Author

Kousik Chakraborty

B.Tech Student | Machine Learning Enthusiast

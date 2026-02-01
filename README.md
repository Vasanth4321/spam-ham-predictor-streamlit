# 📧 Spam/Ham Message Classifier

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://spam-ham-predictor-app-v5jdvpr8xxg5uekbxpcyui.streamlit.app/)

A machine learning-based spam detection application that classifies SMS messages as either **Spam** or **Ham** (Not Spam). This is my first deployment using Streamlit!

## 🚀 Live Demo

**Try the app here:** [Spam/Ham Predictor App](https://spam-ham-predictor-app-v5jdvpr8xxg5uekbxpcyui.streamlit.app/)

## 📋 Project Overview

This application uses Natural Language Processing (NLP) and machine learning techniques to classify SMS messages. The model has been trained on a labeled dataset of spam and ham messages to accurately predict whether a new message is spam or legitimate.

## ✨ Features

- **Real-time Prediction**: Instantly classify messages as spam or ham
- **User-friendly Interface**: Clean and intuitive Streamlit interface
- **Machine Learning Model**: Trained classifier for accurate predictions
- **Text Preprocessing**: Advanced NLP preprocessing pipeline
- **Interactive Web App**: Easy-to-use deployment on Streamlit Cloud

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Streamlit**: Web application framework
- **Scikit-learn**: Machine learning library
- **Pandas**: Data manipulation and analysis
- **NLTK**: Natural Language Processing
- **Pickle**: Model serialization

## 📂 Project Structure

```
spam-ham-predictor-streamlit/
├── app.py                      # Main Streamlit application
├── email_spam_ham.ipynb        # Jupyter notebook for model development
├── preprocessing.py            # Text preprocessing functions
├── spam_email_model.pkl        # Trained ML model
├── email_spam_dataset.csv      # Dataset used for training
├── requirements.txt            # Python dependencies
├── .gitignore                  # Git ignore file
├── LICENSE                     # MIT License
└── README.md                   # Project documentation
```

## 🔧 Installation & Local Setup

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vasanth4321/spam-ham-predictor-streamlit.git
   cd spam-ham-predictor-streamlit
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**
   ```bash
   streamlit run app.py
   ```

4. **Open your browser**
   - The app will automatically open at `http://localhost:8501`

## 💻 Usage

1. Visit the [live demo](https://spam-ham-predictor-app-v5jdvpr8xxg5uekbxpcyui.streamlit.app/) or run locally
2. Enter or paste an SMS message in the text area
3. Click the "Predict" button
4. View the prediction result (Spam or Ham)

## 📊 Model Information

The machine learning model was trained using:
- **Algorithm**: Classification algorithm (e.g., Naive Bayes, Logistic Regression, etc.)
- **Dataset**: SMS Spam Collection Dataset
- **Preprocessing**: Text cleaning, tokenization, stopword removal, and vectorization
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score

## 🎯 Future Enhancements

- [ ] Add model performance metrics visualization
- [ ] Support for multiple languages
- [ ] Bulk message classification
- [ ] Confidence score display
- [ ] Model retraining functionality
- [ ] Email spam detection support

## 👨‍💻 Author

**Vasanth**
- GitHub: [@Vasanth4321](https://github.com/Vasanth4321)
- Location: Hyderabad, Telangana, India

## 🙏 Acknowledgments

- Dataset: SMS Spam Collection Dataset
- Streamlit Community for excellent documentation
- Open-source contributors

## 📞 Contact

For any queries or suggestions, feel free to reach out or open an issue in this repository.

⭐ If you found this project helpful, please consider giving it a star!

**My First Streamlit Deployment** 🎉

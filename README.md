# AI-Powered Fake News Detection with LSTM

## 🚀 Project Overview

This project is an AI-powered fake news detection model built using an advanced Long Short-Term Memory (LSTM) network. The model can accurately classify news text as "Fake News" or "Real News" using Natural Language Processing (NLP) techniques.

## 🔧 Features

* Utilizes LSTM (Long Short-Term Memory) model for advanced text understanding.
* Real-time text prediction through an interactive Streamlit web app.
* Simple, user-friendly interface.

## 📁 Project Structure

* `lstm_fake_news_detector.h5` - The trained LSTM model file.
* `app.py` - The Streamlit app script for real-time predictions.
* `requirements.txt` - List of required Python packages.

## 🚀 Getting Started

### Prerequisites

* Python 3.8 or above
* Git installed

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/fake-news-detection.git
   cd fake-news-detection
   ```

2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the `lstm_fake_news_detector.h5` model file in the directory.

### Running the App

1. Launch the Streamlit app:

   ```bash
   streamlit run app.py
   ```

2. The app will open in your web browser. Enter any news text to test the model.

## 🚀 How It Works

* The text entered by the user is preprocessed using a Tokenizer.
* The LSTM model then analyzes the text and predicts if it is Fake or Real.

## 🔍 Model Details

* The model is an LSTM (Long Short-Term Memory) neural network.
* Trained using a labeled dataset of news articles.
* Optimized for binary classification (Fake or Real).

## 🌐 Deployment

This project can be deployed on Streamlit Cloud for free. You can also deploy it on Heroku or any cloud platform of your choice.

## 🤝 Contributing

Feel free to fork this repository, make improvements, and create a pull request.

## 📄 License

This project is open-source and available under the MIT License.

## 📞 Contact

For any questions or issues, please contact \[Your Name] at \[Your Email].

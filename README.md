# P3-Spam-Email-Classification-using-NLP-and-Machine-Learning

## Spam Mail Classification Project

### Overview
This project is designed to classify emails as either spam or ham using a machine learning model. Here's a concise explanation of the project with its key components and how to run it.


### Objective:
This project objectve is to create a tool that can predict whether an email is spam or ham using natural language processing (NLP) and machine learning.

### Dataset:

A dataset of emails, where each email is tagged as spam or ham.
The dataset is preprocessed to remove noise and transform text data into numerical features.

### Model and Techniques:

- Feature Extraction - Techniques like TF-IDF or Bag of Words convert text into numerical vectors.
- Machine Learning Model - A pre-trained model (ex: Naive Bayes or SVM) is used for classification.

The model is trained on the processed data and stored in pickel file for reuse.
### For Frontend:

We use Built using Streamlit, a lightweight framework for creating interactive web applications.

### For Backend:

We use pre-trained model and vectorizer are loaded using pickle to predict user inputs in real time.
spam.pkl is pre-trained machine learning model and vectorizer.pkl is the vectorizer for transforming text data.

### User Interaction:

The user enters an email into a text box on the web interface.
On clicking the "Classify" button, the app predicts whether the email is spam or ham and displays the result.

## How to Run the Project

1. Download the streamlit in command prompt if this is not avilable .
2. Running the Project
- Open a terminal in the project directory.
- Run the Streamlit app:
- streamlit run spam_detector.py
- after run the streamlit app then open the web application:
- A URL like for example: http://localhost:8501 will appear in the terminal.
3. Using the App
- Enter the email content in the provided text area after that Click on the "Classify" button.
- The app will classify the email and display one of the following messages:
- "This is not a Spam Email".
- "This is a Spam Email".
  by using this steps we will run our project successfully.

### Conclusion
The Spam Mail Classification project effectively demonstrates how machine learning and natural language processing can automate email filtering. By leveraging a pre-trained model and user-friendly interface, the tool accurately classifies emails as spam or ham in real-time, enhancing efficiency and productivity. 






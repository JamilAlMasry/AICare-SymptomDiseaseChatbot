# AICare-SymptomDiseaseChatbot

## The Problem

Many individuals experience symptoms of various illnesses but may not have immediate access to medical professionals for diagnosis. This lack of accessibility can lead to uncertainty, anxiety, and delayed treatment, potentially exacerbating health issues.

## Objective

The objective of this project is to develop an AI-powered chatbot capable of accurately diagnosing diseases based on user-provided symptoms. By leveraging artificial intelligence and natural language processing techniques, the chatbot aims to provide users with immediate and reliable information about their health condition, empowering them to take proactive steps towards seeking appropriate medical care.

## Solution

To address this problem, I developed a chatbot equipped with a machine learning model trained on a comprehensive dataset of symptoms and corresponding diseases. The model utilizes advanced algorithms to analyze user-input symptoms and predict the most likely disease or health condition associated with those symptoms. By employing state-of-the-art techniques in natural language understanding and medical diagnosis, the chatbot offers users personalized and reliable healthcare guidance in real-time.

## Model Used

### Universal Sentence Encoder

The Universal Sentence Encoder (USE) is a versatile natural language processing model developed by Google that converts text inputs into high-dimensional vectors, capturing semantic similarities and contextual nuances. USE is trained on a diverse range of tasks and datasets, enabling it to encode sentences into fixed-length vectors that preserve semantic meaning across various languages and domains. With its ability to understand and represent the meaning of sentences in a universal manner, USE has become a valuable tool for a wide range of NLP applications, including semantic similarity analysis, text classification, and information retrieval. Its efficiency and effectiveness make it an indispensable component in many AI-driven systems seeking to comprehend and process human language accurately and efficiently.

## Dataset Used

Two .csv files containing more than 3000 rows of symptoms and diseases were used for training the model.

## Project Files

The project consists of the following files:

- `AICare_MedicalChatbot.ipynb`: Notebook containing dataset cleaning and model training.
- `AICare_FlaskInterface.ipynb`: Notebook for loading the `Model_USE.h5` and running the Flask app.
- `Model_USE.h5`: Trained machine learning model.
- `Chats.html`: HTML file for the chat interface.
- `label_mapping.json`: JSON file containing the diseases labels and their numerical code
## How to Run?

1. Open `AICare_FlaskInterface.ipynb`.
2. Load the `Model_USE.h5` and configure file paths for the model and HTML file.
3. Run the notebook to start the Flask app.

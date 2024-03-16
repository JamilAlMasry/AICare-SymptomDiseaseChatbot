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

- `AICare_MedicalChatbot.ipynb`: Notebook containing dataset cleaning and model training. [Download from Google Drive](https://drive.google.com/file/d/1Y4Ki3tZjckF7MBO8qWoYQWiwzhrkM8ld/view?usp=sharing) (No need to be run again)
- `AICare_FlaskInterface.ipynb`: Notebook for loading the `Model_USE.h5` and running the Flask app. [Download from Google Drive](https://drive.google.com/file/d/1DbryDoV-AP4d0gv42_mZ03FsnzhcFRCs/view?usp=sharing) (Make sure to change the file paths of the label_mapping.json, chats.html, and model_USE.h5)
- `Model_USE.h5`: Trained machine learning model. The model is almost ~3GB so I didn't upload it to GitHub. It can be cloned from my Google Drive to yours through the following [link](https://drive.google.com/file/d/1Xc8BsonxcuR1l1001XFJTOFo-v42wQP3/view?usp=drive_link). Just make a copy of the model_USE.h5 file to your Google Drive.
- `label_mapping.json`: JSON file containing label mapping. [Download from Google Drive](https://drive.google.com/file/d/1C3u1qMGdJQwckcZTwCRO3rQXnfz-DoqV/view?usp=sharing)
- `chats.html`: HTML file for the chat interface. [Download from Google Drive](https://drive.google.com/file/d/1eqTItxy-WGx-GjO5NN-RUQUnQmQnU6Af/view?usp=sharing)
- `Symptom2Disease.csv`: First part of the dataset. [Download from Google Drive](https://drive.google.com/file/d/1-7Nrpceeiz-AS3rU3HGruXCen6QBlqOf/view?usp=drive_link)
- - `updatedsymptom-disease-train-dataset.csv`: Second part of the dataset. [Download from Google Drive](https://drive.google.com/file/d/13X4K84nBCzyYA47U4PEAWtYXueoXThzS/view?usp=drive_link)
## How to Run?

1. Open `AICare_FlaskInterface.ipynb`.
2. Load the `Model_USE.h5` and configure file paths for the model and HTML file.
3. Run the notebook to start the Flask app.

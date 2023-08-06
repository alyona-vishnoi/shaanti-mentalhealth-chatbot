# Shaanti - Mental Health Chatbot Application
The Mental Health Chatbot is a web-based application built to provide support and resources for mental health-related queries. The chatbot utilizes a Flask-based server and a pre-trained neural network model for natural language understanding (NLU). It aims to offer a compassionate and non-judgmental platform where users can seek information and assistance related to mental health concerns.

<img width="450" alt="Screenshot 2023-08-05 at 10 52 15 PM" src="https://github.com/alyona-vishnoi/shaanti-mentalhealth-chatbot/assets/88257366/f6c7dfd5-e574-4645-800f-11741108aabc"> 

<img width="450" alt="Screenshot 2023-08-05 at 10 56 48 PM" src="https://github.com/alyona-vishnoi/shaanti-mentalhealth-chatbot/assets/88257366/8c986225-7db0-419a-a61f-48e0fe566b6f">

## Features
- **Intent Recognition:** The chatbot can understand user queries and recognize the intent behind the messages. It categorizes the user's input into predefined intents related to mental health topics.
- **Resource Recommendations:** Based on the user's queries, the chatbot provides relevant resources such as helplines that offer information and support for various mental health concerns.
- **Compassionate Responses:** The chatbot is designed to respond in a compassionate and empathetic manner, offering encouragement and support to users seeking help or guidance.

## Technologies Used
- *Flask:* A lightweight Python web framework used to create the server-side application.
- *Natural Language Toolkit (NLTK):* An NLP library used for tokenization, lemmatization, and text processing tasks.
- *Keras with TensorFlow Backend:* A deep learning framework used to build and load the pre-trained neural network model for intent recognition.
- *JSON:* Used to store and handle the intents and responses for the chatbot.
- *HTML, CSS, and JavaScript:* Front-end technologies used to build the user interface of the web application.

## Requirements
Before running the application, you need to have the following installed on your system:
- Python 3.x (Python 3.6 or later recommended)

## Dowloading the code
- You can download the source code for the mental health chatbot application from this repository

## Installation
Once you have downloaded the code, navigate to the project directory and install the required dependencies using pip
  ```
  cd mental-health-chatbot
  pip install nltk numpy keras
  ```

## Running the Application
```
  flask --app app --debug run
```
## Usage
Once the application is running, open your web browser and go to **http://127.0.0.1:5000/**. You will see the chatbot interface on the webpage. You can type your message in the input field and press "Send" to get a response from the chatbot.







## Chatbot Deployment with Flask and JavaScript

Firstly, we need to create a virtual env (.env) and than we activate it.

Afterwards, we follow these instruction:

### 1-Install necessary dependencies

(.env) pip install -r requirements.txt

### 2-Install nltk package

(.env) python
>>> import nltk
>>> nltk.download('punkt')

we create a file JSON 'intents.json' that we can Modify with different intents and responses.

### 3-Run the training program

(.env) python train.py

This will dump data.pth file. And then run.

#### To test it in the console

(.env) python chat.py

the following command to test on interface that we devloped with HTML and CSS:

(.env) python app.py

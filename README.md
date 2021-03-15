# ChatBot
A chatbot is an intelligent piece of software that is capable 
of communicating and performing actions similar to a human. This project
has been made using deep learning techniques. This is the most basic and simplest form
of chatbot using deep learning.The chatbot will be trained on the dataset which 
contains categories (intents), pattern and responses. 
I have used a special recurrent neural network (LSTM) to classify which 
category the user’s message belongs to and then we will 
give a random response from the list of responses.

## Libraries and Packages
- pip install tensorflow
- pip install keras
- pip install pickle
- pip install nltk
- pip install json
- pip install numpy
- pip install random
- pip install tkinter

Or you can simply install all the libraries at once in 
terminal by typing pip install -r requirements.txt

## Intent.json
The data file which has predefined patterns and responses. You can edit patterns and responses
the way you want your chatbot to reply. You can enrich the dataset as much as you want 
by updating this json file.

## Usage
- First you have to run the traindate.py file which will give you another 
file: chatbot_model.h5.
- Then you have to run the chatbox.py file and the program will 
  open up a GUI window within a few seconds. With the GUI you can easily chat with the bot.

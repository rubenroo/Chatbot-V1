# Chatbot-V1
In this repository you will find my efficient AI Chatbot using Python, NLTK, TensorFlow, and Neural networks. I've used the 'Punkt' model from NLTK corpora. The purpose of the project is to demonstrate a chatbot to support 'brussen' (person with disabled sibling).

This chatbot was created using the lessons provided by R. van der Willigen. All his lessons can be found for free on [Github.](https://github.com/robvdw/Digital-Humans) 

**Test it yourself:**
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rubenroo/Chatbot-V1/HEAD?labpath=Chatbot%20code%20Rob%20-%20Ruben%20Feb%202023%20(V1).ipynb)

# How it works
The Chatbot uses a DNN ((Deep Neural Network) to identify patterns in user input and generate a relevant response. The NLTK Library in Python is used to extract relevant words from sentences, reduce them to their root form (stemming), and convert them to numerical values (One-Hot Encoding) for use in the neural network. The neural network is created using Tensorflow's Tflearn library, and trained on a dataset of user queries and corresponding responses. Once trained, the model is able to predict a response to a user's query.

# Why this project
I have done the minor Real Fake, Real Impact. During the minor, I immersed myself in AI and Digital Humans. One of the topics was learning the basics of pyton. With the knowledge learned, I created 4 different chatbots. Each chatbot was built with different techniques and with  diffrent purposes.


# What the chatbot can do
The chatbot demonstrates the techniques mentioned above. The following converstation is possible:

- Say hello to the chatbot
- Ask for tips in case of sleep problems
- Ask to tell a joke with
- Thanks the chatbot 
- Say goodby to the chatbot

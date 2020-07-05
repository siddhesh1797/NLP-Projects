# Chatbot using NLTK & keras

Build a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.

- intents.json – The data file which has predefined patterns and responses.
- Chatbot using NLTK & Keras.ipynb – Build the model and train our chatbot.
- ChatbotGUI.ipynb – Users can easily interact with the bot.
- words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
- classes.pkl – The classes pickle file contains the list of categories.
- chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.

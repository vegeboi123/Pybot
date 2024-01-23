# PyBot README

## Introduction
PyBot is a simple chatbot developed in Python using the Natural Language Toolkit (NLTK) for natural language processing. The chatbot is designed to answer basic queries related to Python programming language and modules. The user interacts with PyBot through a graphical user interface (GUI) developed using Tkinter.

## Files
1. **bot.py:** This file contains the implementation of the PyBot chatbot. It includes functions for processing user input, generating responses using cosine similarity, and handling various types of queries.

2. **gui.py:** This file implements the GUI for the PyBot chatbot using Tkinter. It provides a user interface for entering messages, displaying chat history, and changing the chatbot's settings.

## Dependencies
- Python 3.x
- NLTK library
- Tkinter library
- Scikit-learn library (for TfidfVectorizer and cosine_similarity)
- pyttsx3 library (for text-to-speech functionality)

## How to Run
1. Ensure that you have the required dependencies installed. You can install them using the following command:
2. Run the `gui.py` file using a Python interpreter:
3. The GUI window will appear, allowing you to interact with PyBot.

## Usage
- Enter your messages in the text entry field at the bottom of the GUI.
- Press the "Send" button or hit the "Enter" key to send your message.
- PyBot will process the input and provide a response in the chat window.
- The GUI provides options to change the font and color theme.

## Features
- PyBot can answer basic questions about Python programming language and modules.
- The GUI allows users to customize the appearance by changing the font and color theme.
- Text-to-speech functionality is incorporated, and responses are played using the `pyttsx3` library.

## Additional Notes
- The chatbot uses cosine similarity to find the most relevant response based on the user's input.
- The code includes both the chatbot logic (`bot.py`) and the graphical interface (`gui.py`).
- You can further enhance PyBot by extending the responses and adding more features.

Feel free to explore, modify, and extend this code to suit your needs! If you have any questions or suggestions, please refer to the developers mentioned in the code or reach out to them.

Enjoy chatting with PyBot!



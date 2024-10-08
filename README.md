# Emotional Support Chatbot

One of my graduation projects, this repository contains code and resources to create an intelligent chatbot geared towards human psychology.

## Project Overview

This project involves creating a chatbot that can interact with customers and answer their queries about car models, services, and more. The chatbot uses a pre-trained machine learning model to classify user intents and provide appropriate responses.

## Features

- **Intent Classification**: The chatbot can classify user inputs into predefined intent categories.
- **Dynamic Responses**: Provides responses based on the classified intent.
- **Web Interface**: A simple web interface for interacting with the chatbot.

## Project Structure

- **`intents.json`**: Contains the dataset with patterns and corresponding intent tags used for training the model.
- **`texts.pkl`**: Pickled file containing the vocabulary (unique lemmatized words) used for model training.
- **`labels.pkl`**: Pickled file containing the intent tags (classes) for the model.
- **`model.h5`**: Trained Keras model saved after the training process.
- **`app.py`**: Flask application to serve the chatbot and interact with users through a web interface.
- **`templates/index.html`**: Basic HTML template for the chatbot web interface.

- ## Demo

Here are some screenshots demonstrating the chatbot in action:

![Demo Screenshot 1](demo1.jpeg)
*Figure 1: Chatbot Interface 1

![Demo Screenshot 2](demo2.jpeg)
*Figure 2: Chatbot Interface 2


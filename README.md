# College Assistant Chatbot

This repository contains a **College Assistant Chatbot** web application built using Flask. The chatbot is designed to help students with various tasks such as course information, campus resources, and general queries about college life.

The project includes:
- A Flask server (`app.py`) to handle web requests.
- HTML templates to render the chatbot interface.
- A `requirements.txt` file listing all necessary dependencies.

## Project Structure


### `app.py`
This file contains the main logic of the Flask application, where routes are defined to handle user interactions with the chatbot. It processes user input and serves responses based on predefined logic.

### `requirements.txt`
This file lists all the Python dependencies required to run the Flask application, including any chatbot-related libraries.

### `templates/`
This directory contains the HTML templates used by Flask to render the chatbot user interface.

## Features

- **Chatbot Interface**: A simple chat interface where students can ask questions, and the bot will respond with relevant information.
- **Course Information**: Provides information about courses and departments.
- **Campus Resources**: Offers information about campus facilities, clubs, and events.
- **General Queries**: Handles basic queries related to college life, academic schedules, and more.

## Setup Instructions

Follow these steps to set up the College Assistant Chatbot locally:

### 1. Clone the Repository

Clone the repository to your local machine using the following command:
git clone https://github.com/Ashrith5/Campus-Assist.git
cd college-assistant-chatbot



### 2. Install Virtual Environment

python -m venv venv
venv\Scripts\activate

### 3. Install Dependencies
pip install -r requirements.txt

### 4. Run the Application

After installing the dependencies, you can run the Flask application with:

python app.py


### 5. Open in Browser

Open a web browser and go to http://127.0.0.1:5000/ to interact with the College Assistant Chatbot.


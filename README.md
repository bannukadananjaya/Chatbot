# Chatbot Application

This project implements a chatbot using Flask for the backend and JavaScript for the front end. The chatbot is designed to interact with users, providing information about computer products, assisting with queries, and simulating a conversation interface.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository contains the code for a chatbot designed specifically for a computer shop. The chatbot uses natural language processing to understand user queries and provides appropriate responses. It utilizes a Flask backend for handling requests and responses, while the frontend uses JavaScript to interact with the user.

## Features

- Interactive chat interface
- Handles queries about product information
- Provides support for tech-related issues
- Responsive and intuitive design

## Tech Stack

- **Flask**: Backend framework for handling HTTP requests
- **JavaScript**: Frontend interactivity and user interface
- **PyTorch**: Used for NLP and model development
- **HTML/CSS**: Frontend layout and styling

## Setup and Installation

1. Clone the repository: `git clone https://github.com/bannukadananjaya/Chatbot.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Start the Flask server: `python app.py`

## Usage

1. Access the application at `http://localhost:5000/` in your browser.
2. Enter your queries in the chat interface and interact with the chatbot.

## Project Structure

- `app.py`: Backend code using Flask for handling requests/responses
- `static/`: Contains frontend assets (JavaScript, CSS, images)
- `templates/`: HTML templates for the user interface
- `model.py`: Code for the chatbot model
- `intents.json`: JSON file containing intents for training the chatbot

## Contributing

Contributions are welcome! Fork the repository and create a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).

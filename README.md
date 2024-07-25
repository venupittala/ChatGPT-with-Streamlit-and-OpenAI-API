# ChatGPT-with-Streamlit-and-OpenAI-API
Template for creating your own ChatGPT with Streamlit and OpenAI API
This repository contains the code for a simple web application built with Streamlit, which uses OpenAI's GPT-3 model for generating AI responses in a chat-like interface.

Prerequisites
Python 3.6 or above
An OpenAI API Key
1. Clone the repository to your local machine:

git clone https://github.com/venupittala/ChatGPT-with-Streamlit-and-OpenAI-API.git
2. Navigate to the project directory:

cd streamlit_chatbot_base
Create a virtual environment and activate it:
On macOS and Linux:

python3 -m venv myenv
source myenv/bin/activate
On Windows:

python -m venv myenv
.\myenv\Scripts\activate
3a. Upgrade pip (optional but recommended)

pip install --upgrade pip
Install the necessary Python packages:
pip install -r requirements.txt
Create a .env file in the root directory of the project and add your OpenAI API key:
echo OPENAI_API_KEY=your-api-key > .env
OR

cp .env.example .env
Please replace your-api-key with your actual OpenAI API key.

Run the Streamlit application:
streamlit run chatbot.py
Open a web browser and navigate to http://localhost:8501 to interact with the application.

License This project is open source, under the terms of the MIT license.

Note: This app makes requests to OpenAI's servers whenever the chat is used. Please be aware of this, especially if you're on a paid plan with OpenAI.

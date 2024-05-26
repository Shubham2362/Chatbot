
# Chatbot Project using Hugging Face and Streamlit

This project demonstrates how to deploy a chatbot using the TheBloke/Llama-2-7B-Chat-GGUF model from Hugging Face, integrated with a web interface built with Streamlit, and hosted on Google Colab.


## Table of Contents

- Introduction
- Features
- Installation
- Usage
 
 ## Introduction
This project showcases a conversational AI chatbot leveraging the TheBloke/Llama-2-7B-Chat-GGUF model available on Hugging Face. The chatbot is deployed using Streamlit for the frontend interface, allowing users to interact with the model through a web application. The entire setup is hosted on Google Colab, making it accessible and easy to run without local environment setup.
## Features
State-of-the-art Conversational AI: 
- Utilizes the powerful TheBloke/Llama-2-7B-Chat-GGUF model.
- Web Interface: Easy-to-use interface built with Streamlit.
- Google Colab Hosting: Run the entire application on Google Colab with minimal setup.
## Installation
- Follow these steps to set up and run the project:

## Prerequisites
- A Google account to use Google Colab.
- Basic knowledge of Python and Jupyter notebooks.

## Deployment

 Steps

 1.Clone the repository:
```bash
  git clone https://github.com/yourusername/chatbot-llama2-streamlit.git
cd chatbot-llama2-streamlit
```
2.Open the Google Colab Notebook:

- Go to Google Colab.
- Upload the provided Jupyter notebook (chatbot_colab.ipynb) from the cloned repository.

3.Install required dependencies:

- In the first cell of the Colab notebook, run the following command to install the necessary packages:
```bash
!pip install streamlit transformers
```
4.Download and load the model:
- The notebook contains code to download the TheBloke/Llama-2-7B-Chat-GGUF model from Hugging Face.

5.Run the Streamlit app:
- Execute the following command in a code cell to start the Streamlit server:
```bash
!streamlit run app.py
```
6.Interact with the chatbot:

- After running the above command, a link will be provided in the Colab output.
- Click the link to open the Streamlit web interface and start chatting with the bot.

## Usage
1.Start the Google Colab notebook: Open the chatbot_colab.ipynb notebook in Google Colab.

2.Run all cells: Execute all cells sequentially to set up the environment and start the Streamlit server.

3.Access the web interface: Use the provided link to access the Streamlit application and interact with the chatbot.

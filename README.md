# The Plan
In this tutorial, you will build a text summarization app in React using OpenAI's ChatGPT model.
You will learn how to:

Set up a React project
Install necessary dependencies,
Send a text to the ChatGPT model, and
Extract the summarized text from the model's response.
Additionally, you will discover ways to enhance the text summarization feature.

# Getting started with ChatGPT
To get started with ChatGPT and also get your OpenAI API key, follow these steps:

Log in or create a new account on OpenAI for a free account. By following the instructions, you'll get to your Dashboard. Click on your profile picture to view the menu bar, and then click View API Keys to proceed to the API Keys page.

Click on Create new secret key to create a new API Key.

Copy the API Key and store it safely to use later in the tutorial.

# Installing dependencies such as the OpenAI API client library
The next step is to Install the official OpenAI library, then navigate into the project directory and run the following command:

## npm install openai

# Add the OPENAI_API_KEY in the .env file.
In the project root directory, create a .env file and add the code below:

## REACT_APP_OPENAI_API_KEY = your-api-key-here

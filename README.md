##### Chatbot using Google GeminiAPI #####

## Installation & Setup

[Install Python] https://www.python.org/downloads/ ( You can install depending on your OS)

[Install pip] https://pip.pypa.io/en/stable/installation/

If you have Python & pip installed then check their version in the terminal or command line tools

```
python3 --version
```

```
pip --version
```

## Installing Flask and google.generativeai

In your terminal run the requirements.txt file using this pip

```
pip install -r requirements.txt
```


## Running ChatBot Application in Terminal

```
cd into your directory
```

```
python app.py
```



## What you will create

In this tutorial, I will guide you through the process of building a chatbot that can carry out conversations with users using natural language processing.

We will be using the Gemini API, a powerful tool for generating human-like responses, to handle the natural language processing aspect of the chatbot. The chatbot will be integrated with a Flask backend, a lightweight Python web framework, to create a robust web application capable of interacting with users through a chat interface.

For the frontend, we will design a clean and modern user interface using HTML, CSS, and JavaScript. The user interface will feature a responsive chat layout that enhances user interaction, and jQuery will be used to manage the HTTP requests between the frontend and backend, ensuring smooth communication.

Throughout this guide, I will provide detailed instructions on setting up your development environment, installing necessary dependencies, and writing the code required to build the application. Additionally, I will explain how to effectively use the Gemini API to generate accurate and contextually relevant responses for the chatbot.

By the end of this tutorial, you will have a fully functional chatbot capable of engaging users in conversations, and you will gain valuable experience in using the Gemini API, Flask, and essential web development technologies such as HTML, CSS, and JavaScript.



# User-Html

```
var userHtml = '<div class="d-flex justify-content-end mb-4"><div class="msg_cotainer_send">' + user_input + '<span class="msg_time_send">'+ time + 
    '</span></div><div class="img_cont_msg"><img src="static/images/user_logo.png" class="rounded-circle user_img_msg"></div></div>';
```

# Bot-HTML

```
var botHtml = '<div class="d-flex justify-content-start mb-4"><div class="img_cont_msg"><img src="static/images/user_logo.png" class="rounded-circle user_img_msg"></div><div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></div></div>';
```"# GeminiAPI_chatbot" 
"# GeminiAPI_chatbot" 

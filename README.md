# Internship Project Series

This repository contains two chatbot projects completed during my winter internship with Nexus Software.

## Project 1 - Simple Chatbot

This project involved building a basic chatbot interface with Flask and jQuery.

- The `index.html` file contains the front-end code for the chatbot UI using HTML, CSS, and jQuery. It displays a header, message history, input field, and submit button.
- The `app.py` file handles the back-end logic, routing, and responses for the chatbot using Flask in Python. It has logic to respond to common greetings and questions.
- When the user submits a message, a jQuery AJAX request sends it to the Flask backend. The response is displayed in the chatbox using the bot's avatar image.

This was a great introductory project to learn web development with Flask and jQuery. I gained experience with:

- Building a basic front-end interface with HTML, CSS, JavaScript/jQuery
- Handling form submissions and displaying responses dynamically
- Connecting the front-end to a Python Flask back-end via AJAX
- Setting up routing and responses on the server side
- Saving conversation history in the session
- Displaying bot vs user messages differently in the chatbox

## Project 2 - Knowledge Base Chatbot

This project expanded on the simple chatbot by using a knowledge base to generate responses.

- The `chat.html` file contains the front-end code with some improvements in styling and user experience.
- The Python `app.py` defines a knowledge base dictionary to map pre-defined questions to answers related to college admission.
- When the user asks a question, it checks this knowledge base for a matching answer to respond with.
- Session history is still saved to provide context.

The main learning outcomes were:

- Moving responses from hard-coded logic to an external knowledge base
- Handling a larger variety of natural language questions and mappings
- Improving chatbot conversational ability and accuracy of responses
- Storing and utilizing conversation context and history
- Adding more styling and polish to the chatbot UI

Overall, these projects gave me valuable hands-on experience building chatbots end-to-end using Flask and jQuery, and exposed me to concepts like knowledge bases that I can build on in future projects.

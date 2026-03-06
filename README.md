# ProjectTitle : 

KimiAI Bot –AI Chatbot Using Streamlit and Groq API 

# Description :

KimiAI Bot is a web-based AI chatbot application developed using Python, Streamlit, and the Groq API. The chatbot allows users to interact with an AI language model through a simple and user-friendly chat interface.
The application uses the ( MOONSHOT AI Kimi-K2 Instruct ) model via the Groq API to generate intelligent responses in real-time. It supports streaming responses, meaning users can see the reply being generated live instead of waiting for the full output.
This project demonstrates how modern AI APIs can be integrated with web frameworks to build interactive AI-powered applications.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Features:  

The project includes the following responsibilities and functionalities:
1. User Interface Development 
* Built an interactive web interface using Streamlit
* Designed a chat-style conversation layout
* Implemented user input box for sending messages
  
2. API Integration
* Integrated the Groq API for AI model interaction
* Configured the API key securely using environment variables
  
3. Real-Time Response Streaming
* Implemented streaming responses from the AI model
* Displayed generated text progressively for better user experience
  
4. Chat History Management
* Stored conversation history using Streamlit session state
* Displayed previous user and assistant messages
  
5. Environment Configuration
* Used .env files to securely manage API keys
* Loaded environment variables using dotenv
  
6. Error Handling
* Implemented fallback logic when the model returns an empty response

------------------------------------------------------------------------------------------------------------------------------------------------------------------

# TechnologiesUsed : 

Library ----------------------- Purpose
=======================================

Streamlit -------------------- Build the chatbot web interface

Groq Python SDK--------------- Connect to the Groq AI API

Python------------------------ Core programming language

dotenv ----------------------- Load environment variables fro.envfile

os---------------------------- Access environment variable


# SystemWorkflow : 
1. User enters a message in the chat input.
2. The message is stored in session state.
3. The message is sent to the Groq API.
4. The AI model processes the prompt.
5. The response is streamed back token by token.
6. The chatbot displays the generated response.
7. The conversation history is updated.































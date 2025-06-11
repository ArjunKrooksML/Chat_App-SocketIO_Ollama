A real-time chatbot application using Streamlit and Socket.IO, powered by the Mistral 7B 0.3 language model via Ollama.

Features:
Real-time two-way chat with a locally running LLM
Streamlit-based web UI for interactive usage
WebSocket communication using Python Socket.IO
Dockerized setup for easy deployment
Thread-safe message handling to avoid session crashes

Tech Stack:
-Python 3
-Streamlit
-python-socketio
-requests
-Ollama (for local LLM APIs)
-Docker and Docker Compose

Setup Instructions:

Clone the repository

Make sure Docker and Docker Compose are installed

Run the application:

-bash
-Copy
-Edit

docker-compose up --build

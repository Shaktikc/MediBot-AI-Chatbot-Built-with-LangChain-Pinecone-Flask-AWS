🩺 MediBot: AI Chatbot Built with LangChain, Pinecone, Flask & AWS

I built this project to explore how Large Language Models (LLMs) can be used to create a domain-specific chatbot for healthcare. It was an exciting and hands-on way to combine natural language processing with real-world deployment tools like Flask, Pinecone, and AWS.

This repository contains a complete end-to-end implementation of a Medical Chatbot, covering data embedding, retrieval, and deployment with CI/CD automation.

🔑 Key Components
📚 Data & Embeddings

Text data is embedded using LangChain and stored in Pinecone for fast retrieval.

This allows the chatbot to give context-aware medical responses.

🤖 Chatbot Development

The core chatbot is powered by OpenAI GPT integrated with LangChain.

Flask is used to provide a simple and interactive web interface.

Users can ask health-related questions, and the bot responds in real time.

🌐 Flask Web Application

Run locally to interact with the chatbot through a browser.

Simple and lightweight design for testing and expansion.

☁️ AWS CI/CD Deployment

The project also demonstrates a full deployment pipeline using AWS + GitHub Actions:

Dockerize the Flask app

Push image to Amazon ECR

Deploy on Amazon EC2

Automate updates with GitHub Actions

🛠 Tech Stack

Python

LangChain

Flask

OpenAI GPT

Pinecone

AWS (ECR + EC2)

GitHub Actions (CI/CD)"# MediBot-AI-Chatbot-Built-with-LangChain-Pinecone-Flask-AWS" 

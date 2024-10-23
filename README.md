# Retrieval Augmented Generation (RAG) QA Bot

This project implements a Retrieval Augmented Generation (RAG) model for a QA bot using OpenAI's API and Pinecone as a vector database. The bot is designed to retrieve and augment responses based on user queries.

## Features

- **OpenAI Integration**: Utilizes the OpenAI API to generate embeddings for input queries.
- **Pinecone Vector Database**: Efficiently stores and retrieves document embeddings for quick and accurate responses.
- **Flask API**: A lightweight web server to handle incoming requests and provide responses.
- **Threaded Execution**: Runs the Flask server in a separate thread, allowing simultaneous execution of other code in Google Colab.

## Prerequisites

- Python 3.x
- OpenAI API key
- Pinecone API key

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

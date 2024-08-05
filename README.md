# Chatbot with RAG 

This repository contains a chatbot created using OpenAI's API with LangChain. The chatbot integrates several components to ensure efficient and accurate responses.

## Features

- **OpenAI API**: Used to create the LLM Chain for generating responses.
- **LangChain**: Utilized to structure the language model interactions.
- **Dataset Library**: Loads a webpage to fetch data, with the URL configurable.
- **RAG (Retrieval-Augmented Generation)**: Enhances the bot's efficiency by incorporating contextually relevant information.
- **Pinecone**: Serves as the in-memory vector database for RAG, allowing for effective indexing and retrieval.
- **OpenAI Embedding**: Applied for embeddings with customizable batch size and chunk size.
- **Flowise**: Used for testing the chatbot model to ensure its functionality.

### Prerequisites

- Python 3.x
- Required libraries (install via `pip`):
  - `openai`
  - `langchain`
  - `datasets`
  - `pinecone-client`

### Setup

1. **Clone the Repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install Dependencies:**

3. **Configure the Webpage URL:**

   The URL for the dataset can be replaced as needed in the configuration file or code.

4. **Set Up API Keys:**

   Ensure you have your API keys for OpenAI and Pinecone set up in your environment. You can add these to a `.env` file or directly in the code.

5. **Run the Chatbot:**

   Execute the main script to start the chatbot.

### Usage

Interact with the chatbot via the provided interface or API. The chatbot is designed to fetch and process data efficiently, leveraging the RAG and vector database for enhanced performance.

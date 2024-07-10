# LangChain RAG Chatbot with Mistral-7B

This repository implements a Retrieval-Augmented Generation (RAG) chatbot using the "mistralai/Mistral-7B-Instruct-v0.3" model. The chatbot can fetch content from websites and PDFs, store document vectors using Chroma, and retrieve relevant documents to answer user queries while maintaining chat history for contextual understanding.

## Features

- **Fetch Content:** Retrieves text content from specified URLs and PDFs.
- **Text Splitting:** Splits long documents into manageable chunks for efficient processing.
- **Vector Storage:** Uses Chroma to store document vectors.
- **Retrieval:** Retrieves relevant documents based on user queries.
- **Chat History:** Maintains a history of the conversation for better context in follow-up questions.
- **Customizable Prompts:** Uses a PromptTemplate for generating responses.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/harshith7304/langchain-rag-chatbot.git
   cd langchain-rag-chatbot

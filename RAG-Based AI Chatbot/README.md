# Building a RAG-Based AI Chatbot for Document Search and Retrieval
![Python](https://img.shields.io/badge/python-3.12.5-purple?logo=python&style=plastic)
![Azure](https://img.shields.io/badge/Azure-blue?logo=Azure&style=plastic)

This project demonstrates an **end-to-end workflow** for building an **RAG-Based AI Chatbot for Document Search and Retrieval**. The system utilizes **Azure Document Intelligence**, **Cognitive Search**, and **OpenAI** to enable interactive, context-driven conversations with an AI model based on document content. It combines document retrieval, semantic search, and natural language processing (NLP) to generate responses from relevant documents in real-time.

## Key Features:

- **Data Extraction** from Azure Blob Storage.
- **Custom Index Creation** in Azure Cognitive Search.
- **Embedding Generation** using OpenAI models for semantic search.
- **Integration of AI-powered chatbot** using Retrieval-Augmented Generation (RAG).

## Prerequisites

Before starting, ensure you have the following:

- **Azure Subscription**: Access to **Azure OpenAI**, **Azure Cognitive Search**, and **Azure Document Intelligence**.
- **Azure Resources Setup**: Set up **Azure Cognitive Search**, **Azure Blob Storage**, and **Azure Key Vault** in your Azure subscription.
- **OpenAI Deployment**: A deployed **text-embedding-3-large** or **text-embedding-ada-002** embedding model in Azure OpenAI.

### Environment Setup:
- **Python Version**: 3.12.5 (Use Python 3.10 or later)
- **IDE**: Visual Studio Code with the **Azure extension**. You can test the example inside the **Jupyter extension** in VS Code.


## Running the Notebook
Clone this repository to your local machine or work directly from the GitHub interface.

Install the necessary packages by running:

```
%pip install -r requirements.txt
```

### Configure Environment Variables:

Create a .env file and add your Azure OpenAI API key, Azure Cognitive Search endpoint, and Azure Key Vault details. Example .env file:

```
OPENAI_API_KEY=your-openai-api-key
SEARCH_ENDPOINT=your-azure-search-endpoint
SEARCH_API_KEY=your-azure-search-api-key
KEY_VAULT_URI=your-key-vault-uri
```
Once the environment is set up and the notebook is running, you can start asking questions such as:

- "What documents match the query 'AI-powered chatbot'?"
- "Can you retrieve information about data extraction?"
- "Can you give me specific information about X and Y (based on the documents)"

## Contributing
If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request.

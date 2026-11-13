# Agentic RAG-Based DocuChat

An AI-powered document question-answering application built using **LangChain, Google Gemini, ChromaDB, Hugging Face Embeddings, and Tavily Search**.

### Features
- Extracts and processes text from PDF documents.
- Generates embeddings using Hugging Face.
- Stores and retrieves document chunks using ChromaDB.
- Uses Google Gemini to power an intelligent AI agent.
- Integrates Tavily for real-time web search.
- Dynamically selects PDF retrieval or web search based on user queries.

### Tech Stack
Python | LangChain | Google Gemini | Hugging Face | ChromaDB | Tavily | Google Colab

### How to Run
1. Open the notebook in Google Colab.
2. Install the required dependencies.
3. Add `GEMINI_API_KEY` and `TAVILY_API_KEY` in Colab Secrets.
4. Upload a PDF document.
5. Run all cells and start asking questions.

### Architecture
User Query → Gemini Agent → PDF Retrieval / Web Search → Final Answer

**Note:** API keys are stored securely in Colab Secrets and are not included in this repository.

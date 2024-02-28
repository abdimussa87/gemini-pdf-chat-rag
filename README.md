# gemini-pdf-chat-rag

This repo contains the code for testing Google's Gemini model on interacting with PDFs in a chat manner by utilizing RETRIEVAL AUGMENTED GENERATION(RAG)

## RAG System Overview

RAG, or Retrieval Augmented Generation, is a hybrid AI model that marries the expertise of powerful language models with the richness of external data sources. At its core, RAG leverages a large language model for generating responses, but with a twist – it first retrieves relevant information from a vast pool of external data. This retrieval phase empowers the model to augment its generated responses with information that goes beyond its initial training data, offering more accurate, informed, and context-rich outputs.

## Usage

To run the project, follow these steps:

- Clone the repo: git clone https://github.com/abdimussa87/gemini-pdf-chat-rag
- Install the dependencies: `pip install -r requirements.txt`
- Run the main script:`streamlit run app.py`
- Access the web interface: http://localhost:8501

## References

The project is based on the following references:

- [Langchain for LLM Applications (video course)](https://learn.deeplearning.ai/langchain/lesson/1/introduction)
- [Advanced Retrieval for AI with Chroma (video course)](https://learn.deeplearning.ai/advanced-retrieval-for-ai/lesson/1/introduction)
- [RAGAS Evaluation with Langchain (blog post)](https://blog.langchain.dev/evaluating-rag-pipelines-with-ragas-langsmith/)

# RAG-System-on-Leave-No-Context-Behind-Paper
RAG System on “Leave No Context Behind” Paper
# Overview
This project implements the RAG system based on the "Leave No Context Behind" paper, which combines retrieval-based and generation-based methods to deliver more accurate and contextually relevant responses. The system comprehends context from a given document and generates precise answers to user queries.

# Key Features
# Document Loader
The project utilizes PyPDFLoader to efficiently handle PDF documents. PyPDFLoader extracts text and metadata from PDF files, enabling the system to process a wide range of document formats.

# Text Splitter
NLTKTextSplitter is used to segment documents into smaller, more manageable parts. This segmentation enhances the system's ability to understand complex documents by breaking them down into meaningful segments.

# Vector Store
Chroma serves as the vector store, enabling the system to store and retrieve document embeddings. Document embeddings capture the semantic meaning of documents, allowing for more accurate retrieval and generation of responses.

# Generative AI
GoogleGenerativeAI is leveraged to craft responses based on context. This component uses advanced natural language processing techniques to generate precise and contextually relevant answers to user queries.

# User Interface
The user interface is powered by Streamlit, providing a seamless experience for users to input questions and receive context-aware responses in real-time. The interface is intuitive and user-friendly, making it easy for users to interact with the system.

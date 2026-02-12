## PDF RAG Application – Apple 2024 Annual Report

This project implements a Retrieval-Augmented Generation (RAG) system that allows users to ask questions about a PDF document (Apple Inc. 2024 Annual Report) and get accurate answers using OpenAI + Pinecone.

🚀 Features
-------------------------------------------------------------------
- Load and process large PDF files
- Chunk documents and generate embeddings
- Store embeddings in Pinecone vector database
- Retrieve relevant content using similarity search
- Generate accurate answers using OpenAI LLM
- Prevent hallucinations by answering only from document context


Tech Stack
-------------------------------------------------------------------
- Python
- LangChain
- OpenAI (Embeddings & LLM)
- Pinecone (Vector Database)
- VS Code
- Git & GitHub

Project Structure
-------------------------------------------------------------------
RAG_Practice2/
│
├── data/
│   └── Apple Inc 2024 Annual Report.pdf
│
├── ingest.py        # Loads PDF and stores embeddings in Pinecone
├── query.py         # Ask questions from the stored PDF
├── .env             # API keys and configuration
├── requirements.txt
└── README.md


⚠️ Important Notes
--------------------------------------------------------------------
- Use the same embedding model in both ingest and query files
- Run ingest.py before query.py
- The system answers only from the document context

🎯 Use Cases
------------------------------------------------------------------
- Financial report analysis
- Enterprise document Q&A
- Research paper understanding
- Legal or compliance document search

📌 Future Enhancements
------------------------------------------------------------------

- Streamlit UI for chat interface
- Multi-PDF support
- Source citations with page numbers
- Conversational memory
- Cost optimization


👨‍💻 Author
Jayachandra (Jay)
Data Analyt | RAG & GenAI Enthusiast

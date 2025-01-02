# PDF QnA Backend

This is the backend for the PDF QnA application, which allows users to upload PDF documents, process their contents, and ask questions based on the content of the uploaded PDFs.

## Features

- Upload and process PDF documents.
- Store extracted text in a database.
- Query the stored content using a retrieval-based question-answering system.
- Support for advanced vector-based search using LangChain and ChromaDB.
- Integration with AI models for generating answers to user questions.

---

## Getting Started

### Prerequisites

- Python 3.9 or later
- Pip (Python package manager)
- Virtual environment tools (optional but recommended)

---

### Installation

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd backend

    Set Up a Virtual Environment

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install Dependencies

pip install -r requirements.txt

Set Up Environment Variables Create a .env file in the backend directory and add the following:

    GEMINI_API_KEY=<your-google-genai-api-key>
    OPENAI_API_KEY=<your-openai-api-key>
    DATABASE_URL=sqlite:///./test.db

Usage

    Run the Application Start the backend server:

uvicorn app.main:app --reload

Access the API The backend will be running at:

http://127.0.0.1:8000

API Endpoints:

    Upload PDF: POST /documents/upload
    Ask Question: POST /questions/ask

API Documentation

    Once the server is running, interactive API documentation is available at:
        Swagger UI: http://127.0.0.1:8000/docs
        ReDoc: http://127.0.0.1:8000/redoc
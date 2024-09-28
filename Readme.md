# PDF Document Processing with Langchain

This project demonstrates how to process and analyze PDF documents using Langchain for document embedding, vector store creation, and querying. It uses OpenAI's GPT-4 for generating responses based on the retrieved content.

## Features
- Load and process PDF documents.
- Split large text into manageable chunks.
- Create embeddings and store them in a vector database using Chroma.
- Query relevant information from the vector database.
- Generate structured responses with sources and reasoning.

## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/project-name.git
   cd project-name
   ```

2. **Create a virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Navigate to the application directory**:
   ```bash
   cd app/
   ```

5. **Run the Streamlit app**:
   ```bash
   streamlit run streamlit_app.py
   ```

## How It Works
- The app loads a PDF and splits it into manageable chunks.
- Chunks are converted into embeddings using OpenAI's API and stored in a vector database (Chroma).
- The user can query relevant information from the vector database, and the GPT-4 model generates structured responses with reasoning.

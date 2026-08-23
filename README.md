# Finance RAG Assistant

A Retrieval-Augmented Generation (RAG) application tailored for querying, analyzing, and extracting insights from financial documents, earnings reports, and financial datasets.

---

## 📌 Features

* **Context-Aware Financial QA:** Combines vector retrieval with LLM generation to answer domain-specific finance questions accurately.
* **Modular Retrieval Engine:** Dedicated RAG pipeline (`rag_engine.py`) handling document indexing, vector embeddings, and similarity search.
* **Interactive Interface / API:** Front-end or API entrypoint (`app.py`) for processing queries and displaying responses.
* **Configurable Environment:** Simple secret and API key management via `.env`.

---

## 📁 Repository Structure

```text
├── .env                # Environment variables (API keys, model configs)
├── app.py              # Application entry point / user interface
├── rag_engine.py       # Core RAG retrieval, embedding, and generation logic
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation
```
🚀 Getting Started
```text
1. Prerequisites
Python 3.9+ installed on your machine.
API key for your chosen LLM and embedding provider (e.g., OpenAI).

2. Clone the Repository
git clone [https://github.com/srivatsan1892/RAG-Finance-Project.git](https://github.com/srivatsan1892/RAG-Finance-Project.git)
cd RAG-Finance-Project


3. Set Up Virtual Environment

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Linux/macOS:
source venv/bin/activate
# On Windows:
venv\Scripts\activate

4. Install Dependencies
Bash
pip install -r requirements.txt
5. Environment Configuration
Create or update your .env file in the root directory:

Code snippet
OPENAI_API_KEY=your_openai_api_key_here

# Add other relevant environment variables (ChromaDB)
💻 Usage
Run the main application:
python app.py
```

🛠️ Tech Stack
Language: Python

RAG Framework: LangChain / LlamaIndex

Vector Store: Chroma (configure as needed)

LLMs & Embeddings: OpenAI


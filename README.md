# LegalRAG

Law is an **AI-powered legal chatbot** designed to assist users with queries related to **Indian law**. It provides
accurate legal information based on general legal knowledge and user-uploaded PDF documents. The chatbot is available
via a **`FastAPI` backend API** and a **`Streamlit`-based web interface**.

---

## 🚀 Features

✅ **Conversational AI:** Provides informative responses to legal queries.  
✅ **Indian Law Focused:** Tailored to Indian legal statutes and regulations.  
✅ **PDF Processing:** Extracts relevant text from uploaded legal documents.  
✅ **Vector Search:** Uses `ChromaDB` for efficient document retrieval.  
✅ **Streaming AI Responses:** Powered by `Groq's Llama-3 model`.  
✅ **FastAPI Backend:** `REST` API endpoints for integration with other applications.

---

## 🛠 Tech Stack

### **Backend (FastAPI)**

- **FastAPI** (REST API framework)
- **LangChain** (LLM-powered legal chatbot)
- **Groq (Llama-3.3-70B)** (LLM for AI responses)
- **ChromaDB** (Vector search for legal text retrieval)
- **Hugging Face Embeddings** (Text vectorization)
- **PyPDFLoader** (PDF text extraction)
- **Uvicorn** (ASGI server for FastAPI)

### **Frontend (Streamlit)**

- **Streamlit** (Web interface for chatbot interaction)

---

## 📌 Setup Instructions

| Method | Endpoint            | Description                             |
|--------|---------------------|-----------------------------------------|
| GET    | `/get_legal_advice` | Gets legal advice based on a user query |
| POST   | `/upload_pdf`       | Uploads and processes a PDF document    |
| POST   | `/clear_chat`       | Clears the chat history                 |

---


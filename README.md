# Math RAG Assistant

An AI assistant for advanced mathematics questions using Retrieval-Augmented Generation (RAG).

This project enables a user to ask math-related questions (theorems, proofs, formulas) and receive responses based on retrieved content from textbooks, lecture notes, or academic papers (PDFs).

---

##  Features

-  PDF ingestion & chunking
-  Vector indexing with FAISS
-  Lightweight local LLM support (TinyLlama or similar)
-  RAG pipeline using LangChain
-  Prompt engineering for improved response quality

---

##  Tech Stack

- Python
- LangChain
- FAISS
- Hugging Face Transformers
- SentencePiece / Tokenizer
- Local LLM (TinyLlama, Mistral-tiny, etc.)
- PyPDF or similar PDF loader

---

##  Current Limitations

- Due to limited resources, this assistant currently uses a **small open-source model**.
- Responses may lack accuracy or depth for complex questions.
- However, the architecture fully supports **switching to larger models via API**, such as:
  - OpenAI (gpt-3.5, gpt-4)
  - Groq
  - Together.ai
  - Mistral Inference API

---

## Future Plans

- Add support for more powerful models (OpenAI, Mistral, etc.)
- Enable multi-source retrieval (multiple books or documents)
- Add conversational memory for follow-up questions

---

##  Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/math-rag-assistant.git
cd math-rag-assistant
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the app
```bash
jupyter notebook AI_Math_Assistant.ipynb
```

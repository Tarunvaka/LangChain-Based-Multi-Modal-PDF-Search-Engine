# LangChain-Based-Multi-Modal-PDF-Search-Engine 
This project is a Retrieval-Augmented Generation (RAG) pipeline that enables intelligent question-answering from PDF documents using both **textual** and **visual** content (e.g., images, tables). Built with [LangChain](https://www.langchain.com/), it integrates tools like `unstructured`, OpenAI/Groq LLMs, and `ChromaDB` for multi-modal document understanding. 

--- 

## 📌 Features 
- 🔍 Extracts **text, tables, and images** from PDFs using `unstructured`
- 🧠 Embeds document chunks into a **vector store** (ChromaDB)
- 💬 Enables **semantic search** and **question answering** with LLMs
- 🧾 Handles large documents with chunking strategies and high-resolution PDF parsing
- 🧰 Uses LangChain for chaining multi-modal inputs and outputs

---

## 🛠️ Tech Stack 
- **LangChain** — framework for building LLM-powered apps
- **Unstructured** — document parsing (text, images, tables)
- **ChromaDB** — vector store for semantic retrieval
- **OpenAI / Groq API** — LLMs for answering queries
- **Python, Jupyter Notebook**

---

## 🖼️ Example Use Case 
- **Input**: A PDF document with rich content (e.g., charts, paragraphs, tables)
- **Query**: "What is the key insight from the chart on page 3?"
- **Output**: A relevant LLM-generated answer leveraging both text and image data

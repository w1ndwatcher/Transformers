# NLP & RAG Essentials with LangChain, FAISS, and HuggingFace

This repository contains a hands-on learning journey through key concepts in **Natural Language Processing (NLP)**, **custom tokenization**, **embeddings**, **vector databases**, and **LangChain** components, culminating in a **RAG-based PDF Question Answering chatbot project**.

---

## 📂 Repository Structure

| Notebook | Description |
|----------|-------------|
| `01_Creating_a_custom_tokenizer.ipynb` | Create a custom tokenizer using BPE and pre-trained tokenizer using HuggingFace Tokenizers. Introduces basic tokenization concepts. |
| `02_Embeddings.ipynb` | Generate text embeddings using the `instructor-xl` model from HuggingFace. |
| `03_FAISS_Indexing.ipynb` | Store and retrieve embeddings using **FAISS** (Facebook AI Similarity Search). |
| `04_LangChain_Essentials.ipynb` | Explore LangChain components through an interactive **tour guide assistant** example. Covers: **Models** (OpenAI/Groq), **Prompts** (PromptTemplate), **Memory** (ChatBufferMemory), **Vector Stores** (FAISS), **Chains** (Activity + Tips), **Agents** |
| `05_Chat_with_PDFs_Project.ipynb` | Final RAG project where users can upload PDFs and chat with the content using a **retrieval-augmented generation pipeline**. |

---

## 🛠️ Skills & Technologies

- **Custom & Pre-trained Tokenization** – HuggingFace Tokenizers
- **Embeddings** – `instructor-xl` from HuggingFace
- **FAISS** – Efficient similarity search
- **LangChain** – Modular chains, memory, prompts, tools, and agents
- **Retrieval-Augmented Generation (RAG)** – For building context-aware chatbots
- **OpenAI/Groq APIs** – LLM-based responses

---

## 💡 Use Case Highlights

- **Understand tokenization**: Build intuition behind how text is broken down for NLP tasks.
- **Embed real-world text**: Use domain-specific instructions to guide embedding generation.
- **Powerful retrieval**: Build a FAISS index for fast, semantic retrieval.
- **LangChain mastery**: Build assistants and agents that use memory, prompts, and chains.
- **QA over documents**: Upload PDFs and ask questions powered by RAG pipeline.

---

## 📌 Getting Started

1. Setup secret keys for Hugging Face and Groq/OpenAI and save them in a .env file.
2. Run the notebooks using Jupyter/Colab.

---

## 📚 Ideal For

- NLP learners and enthusiasts
- RAG and LangChain practitioners
- Instructors teaching modern LLM/NLP stacks
- Anyone building a document QA chatbot

# 📄 Project Report: Multilingual Legal RAG (Retrieval-Augmented Generation)

## 🔍 Project Overview

This project aims to develop a **fully open-source Retrieval-Augmented Generation (RAG) system** from scratch for the **legal domain**, supporting **multilingual queries and responses**. The system will be trained without the use of any closed-source APIs or pre-trained LLMs, ensuring a transparent, modular, and research-oriented architecture.

## 🎯 Objective

- Build a **custom tokenizer, encoder, decoder, and retriever pipeline**.
- Create and preprocess a **high-volume legal text corpus** (multilingual).
- Train the full model architecture on CPU first and scale to GPU later.
- Implement a **FAISS-based retriever** integrated with a Transformer-based generator.
- Evaluate performance on legal question-answering tasks.

- ## 📁 Current Directory Structure

- legal-law-RAG/
├── data/
│ ├── raw/ # Raw legal documents
│ └── processed/ # Cleaned and tokenized data
├── notebooks/ # Jupyter notebooks for each stage
├── src/ # Core Python modules
├── models/
│ ├── tokenizer/
│ ├── encoder/
│ └── decoder/
├── faiss_index/ # FAISS vector storage
├── README.md
├── requirements.txt
└── project_report.md

## 🔧 Stack

- **Language**: Python
- **Frameworks**: PyTorch, Hugging Face Tokenizers (for custom training), FAISS
- **Notebook Environment**: Jupyter (initially local, scalable to PARAM Siddhi)
- **Tools**: Git, VS Code, Markdown

## 🧠 Key Highlights

- 💡 Multilingual support for diverse legal datasets
- 🔐 100% open-source pipeline (no API keys or black-box models)
- ⚙️ Modular design: plug-and-play components for training, indexing, and inference
- 📈 Scalable: designed to transition from CPU to HPC-GPU infrastructure

## 🚧 Next Steps

- [x] Setup initial repo and directory structure
- [ ] Collect and clean multilingual legal text data
- [ ] Train a custom tokenizer
- [ ] Develop and train encoder-decoder architecture
- [ ] Build and integrate FAISS retriever
- [ ] Evaluate RAG performance on legal QA tasks

---

> _Maintained by Yash Pawar_  
> _Project Engineer, CDAC 

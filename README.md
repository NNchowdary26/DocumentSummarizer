# 🧠 Document Summarizer with Transformers (Google Colab)

This project is a **Document Summarizer** built in **Python** and designed to run in **Google Colab**. It allows users to upload `.pdf`, `.docx`, or `.csv` files and receive a high-quality, AI-generated summary using Hugging Face's `transformers` library.

## 🚀 Features

- 🔍 **Supports Multiple File Types**: Upload and summarize `.pdf`, `.docx`, and `.csv` files.
- ✂️ **Chunking for Long Documents**: Automatically splits large documents into manageable pieces for accurate summarization.
- 🤖 **State-of-the-Art Summarization**: Uses `facebook/bart-large-cnn` for summarizing content with excellent results.
- 📚 **Easy to Use in Google Colab**: Designed for an interactive and beginner-friendly workflow.

## 📦 Requirements

Make sure you install these dependencies in your Colab environment:

```bash
!pip install transformers
!pip install python-docx
!pip install PyPDF2
!pip install sentencepiece

# 📄 AI PDF Reader

**AI PDF Reader** is a smart Colab-based tool that allows users to upload a PDF, automatically analyze its content, and:

- 📋 Generate concise summaries
- 🌐 Translate summaries into multiple languages (Hindi, Spanish, French)
- ❓ Answer natural language questions based on the PDF content

This makes it ideal for researchers, students, and professionals working with long or complex documents.

---

## 🚀 Features

- 📤 Upload any PDF file
- 🧠 Full-text extraction and summarization using BART
- 🌍 Multilingual translation of the summary
- 💬 Interactive question-answering powered by RoBERTa
- 🧪 Lightweight, runs entirely in Google Colab

---

## 🧠 Technologies Used

- [`pdfplumber`](https://github.com/jsvine/pdfplumber) for PDF text extraction
- 🤗 [`Transformers`](https://huggingface.co/transformers/) (BART for summarization, RoBERTa for Q&A)
- [`googletrans`](https://py-googletrans.readthedocs.io/) for translation
- `ipywidgets` for interactive UI in Jupyter/Colab

---

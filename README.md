# 📝 PDFusion Chat

A Natural Language Processing application that lets users chat with multiple PDF documents using **LangChain** and **Google Gemini API Key**, enabling seamless interaction, extraction, and analysis of information across files.

---

## 🌐 Tech Stack

| Component     | Technologies Used                        |
|----------------|---------------------------------|
| **Framework**    | LangChain |
| **LLM API**       | Google Gemini (Gemini Pro) |
| **Frontend**      | Streamlit |
| **Backend**       | Python |
| **Document Parsing** | PyPDF |

---

## ✨ Features

- 📂 **Multi-PDF Upload**: Upload and manage multiple PDFs at once.
- 💬 **Interactive Chat Interface**: Ask questions across all uploaded documents.
- 🔍 **Contextual Understanding**: Answers are derived by comprehending content across PDFs.
- 🧠 **NLP-Powered Responses**: Uses **LangChain** for conversational logic and **Gemini Pro** for powerful language understanding.
- 📊 **Document Insights**: Extracts and displays key insights and summaries.
- 🗂️ **History Tracking**: Tracks your chat history for reference.

---

## 📋 Requirements

Ensure the following are installed and available:

1. **Python 3.9+** ➡️ [Download Python](https://www.python.org/downloads/)
2. **Google Gemini API Key** ➡️ [Get API Key](https://aistudio.google.com/app/apikey)
3. **Visual Studio Code** (Recommended IDE) ➡️ [Download VS Code](https://code.visualstudio.com/)

---

## ⚙️ Setup & Installation Guide

### Clone the Repository

```bash
git clone https://github.com/your-username/PDFusion-Chat.git
```

### Create & Activate Virtual Environment

```bash
cd PDFusion-Chat

# Create virtual environment
python -m venv venvpdf

# Activate virtual environment
# On Windows
venvpdf\Scripts\activate

# On Mac/Linux
source venvpdf/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Add Your Google Gemini API Key

Create a `.env` file in the project root with the following content:

```
GEMINI_API_KEY=your-google-gemini-api-key
```

### Run the Application

```bash
streamlit run app.py
```

---


## 👀 Preview


## 🤝 Contribute & Feedback

We welcome contributions, feature requests, and feedback! Feel free to open an **Issue** or **Pull Request**.

---

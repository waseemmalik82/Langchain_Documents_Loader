# LangChain Documents Loader

A practical implementation of LangChain's Document Loaders for loading data from various sources including PDFs, CSVs, Text files, Web pages, and Directories.

---

## 📁 Project Structure
Langchain_Documents_Loader/
├── text_loader.py
├── csv_loader.py
├── PyPDF_loader.py
├── WebBase_Loader.py
├── Directory_loader.py
├── cricket.txt
├── Social_Network_Ads.csv
├── dl-curriculum.pdf

---

## 🧠 Files Overview

| File | Description |
|---|---|
| `text_loader.py` | Load data from plain text files |
| `csv_loader.py` | Load data from CSV files |
| `PyPDF_loader.py` | Load data from PDF files |
| `WebBase_Loader.py` | Load data from web pages |
| `Directory_loader.py` | Load all files from a directory |
| `cricket.txt` | Sample text file for testing |
| `Social_Network_Ads.csv` | Sample CSV file for testing |
| `dl-curriculum.pdf` | Sample PDF file for testing |

---

## 🔗 Document Loaders Explained

### 1. Text Loader 📄
Loads plain text files into LangChain documents.
cricket.txt → TextLoader → LangChain Document
### 2. CSV Loader 📊
Loads CSV files and converts each row into a LangChain document.
Social_Network_Ads.csv → CSVLoader → LangChain Documents
### 3. PyPDF Loader 📑
Loads PDF files and extracts text from each page.
dl-curriculum.pdf → PyPDFLoader → LangChain Documents
### 4. WebBase Loader 🌐
Loads content directly from any web page URL.
URL → WebBaseLoader → LangChain Document
### 5. Directory Loader 📁
Loads all files from an entire directory at once.
Folder → DirectoryLoader → Multiple LangChain Documents
---

## ⚙️ Setup & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/waseemmalik82/Langchain_Documents_Loader.git
cd Langchain_Documents_Loader
```

### 2. Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Setup API Keys
Create a `.env` file in the root folder:
OPENAI_API_KEY=your_openai_key

---

## 🚀 Usage

```bash
# Text Loader
python text_loader.py

# CSV Loader
python csv_loader.py

# PDF Loader
python PyPDF_loader.py

# Web Base Loader
python WebBase_Loader.py

# Directory Loader
python Directory_loader.py
```

---

## 🛡️ Important

- Never share your `.env` file
- `.env` is added to `.gitignore` for security
- Keep your API keys private at all times

---

## 👨‍💻 Author

**Waseem Malik**
GitHub: [@waseemmalik82](https://github.com/waseemmalik82)

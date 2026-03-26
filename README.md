# 📄 PDFQuery with LangChain

Query PDF documents using **LangChain** and a **SimpleChain**.  
This project extracts text from PDFs and allows natural language Q&A.

---

## 🚀 Features

- Extract text from PDF files  
- Use **LangChain SimpleChain** with a **PromptTemplate**  
- Ask questions about PDF content  
- Get AI-generated answers based on the document  

---

## 🛠️ Tech Stack

- Python  
- LangChain  
- OpenAI  
- PyPDF / PDFPlumber  

---

## 📌 How It Works

1. Load PDF and extract text.  
2. Store extracted text as context.  
3. User asks a question.  
4. LangChain **PromptTemplate** formats the question + PDF content.  
5. LLMChain sends the prompt to the LLM.  
6. Receive AI-generated answer based on the PDF.  

---

## ⚙️ Installation

```bash
git clone https://github.com/hemasreeuvs/pdfquery_langchain.git
cd pdfquery_langchain
pip install -r requirements.txt

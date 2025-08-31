# 🗃️ Talk2YourData 

**Talk2YourData** is an **intelligent document assistant** built with [Streamlit](https://streamlit.io/).  
It allows users to upload your **Own documents (PDF)** and interact with them through a chat interface.  

The application uses a **Retrieval-Augmented Generation (RAG)** pipeline to retrieve relevant information from uploaded documents and generate accurate, context-aware answers.

---

## ✨ Core Features

- 📂 **Document Upload**  
  Upload one or more PDF files through a simple web interface.  

- 📝 **Text Extraction & Processing**  
  Extract text from PDFs, split into manageable chunks, and convert into numerical **vector embeddings**.  

- 📦 **Vector Storage**  
  Store embeddings in a **FAISS vector database** for efficient similarity searching.  

- 💬 **Chat Interface**  
  Ask questions in a user-friendly chat interface.  

- 🤖 **Retrieval & Generation**  
  Relevant chunks are retrieved and passed to a **Large Language Model (LLM)** to generate context-aware answers.  

---

## 🚀 Tech Stack

- [Streamlit](https://streamlit.io/) – Frontend & App Framework  
- [FAISS](https://github.com/facebookresearch/faiss) – Vector Database  
- [LangChain](https://www.langchain.com/) – RAG Pipeline  
- [OpenAI API](https://platform.openai.com/) – Large Language Model  
- [PyPDF2 / pdfplumber] – PDF text extraction  

---

## 📌 Usage

1. Upload one or more PDF medical documents.  
2. Ask your document-related questions in the chat.  
3. Get **accurate, contextual answers** powered by RAG + LLM.  

---

## 🔒 Security Note

- API keys and sensitive configs are managed using a `.env` file (not pushed to GitHub).  
- Use **Streamlit Cloud secrets** or **Hugging Face Spaces secrets** when deploying.  

---

## 🛠️ Future Improvements

- ✅ Support for multiple document formats (DOCX, TXT).  
- ✅ Enhanced UI with history tracking.  
- ✅ Deployment on Hugging Face Spaces / Streamlit Cloud.  

---
## 📷 Demo
Application is up and running at: [Talk2YourData](https://talk2yourdata.streamlit.app/)


### Landing Page:
<img width="1512" height="947" alt="image" src="<img width="2852" height="1524" alt="image" src="https://github.com/user-attachments/assets/6e985d03-de1d-4b42-8419-7c42df6d42e1"/>

### Upload Files:
<img width="1512" height="946" alt="image" src="<img width="2864" height="1534" alt="image" src="https://github.com/user-attachments/assets/4a71de5b-378d-49b4-863a-502c78ed1812"/>


### Assistant in Action:
<img width="1512" height="939" alt="image" src="<img width="2862" height="1526" alt="image" src="https://github.com/user-attachments/assets/8a049b5a-990a-4b14-8817-b0f211a70188"/>




---

## 👨‍💻 Author

Developed by **Santosh Vishwakarma** 🚀  

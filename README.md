# Chat with PDF using Gemini AI 📚💬

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Google AI](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)

This application revolutionizes the way you interact with PDF documents by leveraging Google's advanced Gemini AI technology. Upload your PDF files, and engage in natural conversations about their content, receiving detailed, contextually accurate responses directly from your documents. Perfect for researchers, students, professionals, or anyone looking to quickly extract insights from large PDF files without having to read through everything manually.

## ✨ Features

- **Multiple PDF Support**: Upload and analyze several PDF documents simultaneously
- **Intelligent Text Extraction**: Automatically processes and extracts text from complex PDF structures
- **Advanced Vector Embeddings**: Utilizes Google's state-of-the-art embedding model (models/embedding-001) to understand document semantics
- **Contextual Question Answering**: Ask questions in natural language about your documents
- **High-Quality AI Responses**: Powered by Google's Gemini 1.5 Flash model for accurate, relevant, and detailed answers
- **Intuitive User Interface**: Clean, user-friendly Streamlit interface requires no technical expertise
- **Fast Processing**: Efficiently handles large documents with optimized text chunking and vector storage
- **Semantic Search**: Finds the most relevant parts of your documents to answer specific questions

## How to Use

1. Upload your PDF files using the sidebar
2. Click "Submit & Process" to extract and index the content
3. Ask questions in the text input field
4. Get AI-generated answers based on the content of your PDFs

## Technologies Used

- Streamlit for the web interface
- Google Gemini AI for generating responses
- LangChain for text processing and chain creation
- FAISS for vector similarity search
- PyPDF2 for PDF text extraction

## Setup for Local Development

1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Create a `.env` file with your Google API Key: `GOOGLE_API_KEY=your_api_key_here`
4. Run the app: `streamlit run app.py`

<div align="center">Made with ❤️ by Saksham Goel</div>

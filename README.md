# 📄 PDF Answering AI

A question-answering demo powered by vector search, utilizing Astra DB and LangChain. PDF Answering AI is an interactive tool that uses natural language processing and AI models to answer questions based on the content of uploaded PDF documents. It’s ideal for extracting insights from research papers, manuals, reports, and other long-form documents without having to read them end to end.


---

## 🧠 Features

- **Smart PDF Reading**: Automatically extracts text from PDF files.
- **Contextual Answering**: Uses language models to answer questions based on the actual content.
- **Embeddings & Vector Search**: Finds the most relevant sections using similarity search.
- **Interactive Interface**: Easily ask follow-up questions in a conversational manner.

---

## 📂 Typical Workflow

1. **Upload PDF**: User provides a PDF document.
2. **Text Extraction**: The tool reads and extracts text from the PDF.
3. **Chunking and Embedding**: The text is divided into manageable chunks and converted into vector embeddings.
4. **Query Input**: User inputs a natural language question.
5. **Context Retrieval**: The system searches for the most relevant text chunks.
6. **Answer Generation**: A language model generates a response based on the selected context.

---

## 💡 Use Cases

- Research assistance  
- Document summarization  
- Legal or academic paper analysis  
- Knowledge management for businesses  

---

## 🔧 Technologies Used

- Python 3.8+
- [LangChain](https://www.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [FAISS](https://github.com/facebookresearch/faiss) or ChromaDB
- [PyMuPDF](https://pymupdf.readthedocs.io/en/latest/)
- [tiktoken](https://github.com/openai/tiktoken)
- Streamlit (optional for GUI)

---

## 📦 Installation

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/pdf-answering-ai.git
cd pdf-answering-ai

### 2. Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate






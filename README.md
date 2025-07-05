# langchain-multiformat-loader-lab
A hands-on GenAI project showcasing the use of various document loaders in LangChain — including PDF, CSV, JSON, Markdown, Office Docs, and more — for building adaptable and robust RAG pipelines with OpenAI.
----
````markdown
# 🧠 LangChain Multi-Format Loader Lab

A practical GenAI project to experiment with and compare different **LangChain document loaders**. This project covers loaders for PDFs, CSVs, JSON, DOCX, Markdown, directories, and more. It's designed for developers building **RAG (Retrieval-Augmented Generation)** systems using unstructured data in different formats.

---

## 🎯 Objective

To understand and compare various LangChain loaders and unstructured.io methods for document processing, enabling advanced chunking, parsing, and RAG integration.

---

## 🚀 Features

✅ Compare LangChain native loaders vs Unstructured.io loaders  
✅ Load documents like PDFs, CSVs, Word, Markdown, JSON, and directories  
✅ Demonstrate section-based chunking and metadata handling  
✅ Perform selective extraction from JSON  
✅ Work with raw Unstructured APIs for deeper control  
✅ Ideal for GenAI use cases like chatbots, semantic search, and summarization

---

## 📁 Loaders Covered

1. **TextLoader**
2. **MarkdownLoader**
3. **CSVLoader** (with csv_args & Unstructured parsing)
4. **JSONLoader** (with field-based value extraction)
5. **PDFLoader**
   - PyPDFLoader
   - PyMuPDFLoader
   - UnstructuredPDFLoader
   - Raw API-based PDF parsing
6. **Microsoft Office Loaders**
   - Word (single + complex chunking)
7. **DirectoryLoader** (with auto-format detection)

---

## 🛠 Tech Stack

- 🧠 LangChain  
- 🔍 Unstructured.io  
- 🤖 LangChain Community & OpenAI  
- 📄 PyPDF2, PyMuPDF, python-docx  
- 📦 Python 3.11+

---

## 🧪 Setup

```bash
pip install langchain
pip install langchain_openai
pip install langchain_community
pip install "unstructured[all-docs]==0.14.0"
````

---

## 🧑‍💻 Sample Use Case

This project prepares the ground for:

* Resume matchers
* PDF question answering
* Research paper parsing
* Smart chatbot pipelines

---

## 🧠 Skills Learned

* LangChain ecosystem and loader design
* Deep comparison: LangChain vs Unstructured.io
* File parsing and text extraction in real-world formats
* Prompt tuning with extracted content
* Chunking strategies and metadata tracking
* Custom document processing logic in GenAI pipelines

---



## 📜 License

This project is licensed under the MIT License.

---

## 🤝 Author

**Govinda Tak**
📧 [govindatak19@gmail.com](mailto:govindatak19@gmail.com)
🔗 [GitHub](https://github.com/Govinda-Tak)


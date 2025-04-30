

---

## 🧠 Simple Gen AI App using LangChain

This project demonstrates how to build a basic Generative AI application using **LangChain**, integrating web scraping, document retrieval, and OpenAI's API to answer user queries intelligently.

### 🚀 Features

- Web scraping to ingest dynamic content from URLs.
- Document loading and indexing for contextual search.
- LangChain retriever for relevant document selection.
- OpenAI integration for generating human-like responses.
- Environment setup with `.env` variables for secure API key management.

### 🛠️ Tech Stack

- Python
- LangChain
- OpenAI API
- dotenv
- WebBaseLoader (for scraping)

### 📦 Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://your-repo-url.git
   cd your-repo-folder
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**

   Create a `.env` file and add the following keys:

   ```
   OPENAI_API_KEY=your_openai_key
   LANGCHAIN_API_KEY=your_langchain_key
   LANGCHAIN_PROJECT=your_project_name
   ```

5. **Run the notebook:**

   Use Jupyter Notebook or Jupyter Lab to open and run `1.2.1-Simpleapp.ipynb`.

### 📌 Notes

- Make sure your OpenAI and LangChain API keys are active and have sufficient quota.
- Customize the WebBaseLoader with your target URLs for scraping.

---


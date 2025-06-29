# 🤖 QuickBot – A Lightweight Q&A Chatbot

QuickBot is a lightweight, modular chatbot built in Python that answers user queries using a language model backend. It supports basic retrieval-augmented generation (RAG), memory, and streaming responses.

## 🚀 Features

- 🔍 Ask questions and get intelligent answers
- 📚 Retrieval from custom documents (RAG)
- 💬 Streaming token-by-token output (typing effect)
- 🧠 Optional memory to hold context
- 🛠️ Easily extendable for new features or data sources

## 🧱 Built With

- Python 3.10+
- [Pydantic](https://docs.pydantic.dev/) – data validation
- [FastAPI](https://fastapi.tiangolo.com/) – web API interface
- [LangChain](https://www.langchain.com/) – GenAI framework
- [OpenAI](https://platform.openai.com/) or AWS Bedrock – LLM backend

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/quickbot.git
cd quickbot

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

_

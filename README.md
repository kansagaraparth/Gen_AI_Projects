# LangChain_GenAI_Projects

This repository contains multiple projects built using LangChain and Generative AI models such as Gemini Pro and OpenAI's GPT. Each project demonstrates a specific use case or capability of LangChain, including prompt handling, retrieval-based QA, agent tools, and more.

## Projects

- Prompt Playground – Simple UI for testing prompts with Gemini via LangChain.
- Retrieval QA – Uses vector-based retrieval to answer queries from documents.
- Agent Demo – Demonstrates LangChain agents with tool calling.
- LLM Comparison – Compares outputs of different models using a unified interface.

## Tech Stack

- Python 3.10+
- LangChain
- Gemini Pro (Google GenAI)
- OpenAI API
- Streamlit
- FAISS or Chroma (for vector stores)

## Setup

1. Clone the repository:

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

2. Intsall Dependecies
```bash
pip install -r requirements.txt
```

3. Setupt your env files with API keys 
- GOOGLE_API_KEY=your_google_genai_api_key
- OPENAI_API_KEY=your_openai_api_key

4. Run with streanlit

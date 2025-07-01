# 🤖 Advanced AI Agent for Developer Tools Research

This project is an **Advanced AI Agent** designed to help developers research and evaluate developer tools quickly. It integrates the power of **LangChain**, **LangGraph**, **Firecrawl**, and **OpenAI** to analyze and summarize data about developer products across the web.

---

## 🚀 Features

- 🔍 Natural language interface for querying developer tools
- 🌐 Automated web crawling using Firecrawl
- 🧠 Intelligent reasoning via OpenAI's GPT
- 🧰 Tool-based architecture using LangGraph + LangChain
- 📊 Outputs include company details, pricing, API availability, language support, tech stack, and integration capabilities
- 📝 Developer recommendations and summaries

---

## 🧠 How It Works

1. User enters a query about developer tools.
2. Firecrawl retrieves web content and pages.
3. LangChain + OpenAI analyze the structured data.
4. Results are displayed in a clean, readable format.

---

## 🧪 Example Output

```
🔍 Developer Tools Query: AI vector databases

📊 Results for: AI vector databases
============================================================

1. 🏢 Weaviate
   🌐 Website: https://weaviate.io
   💰 Pricing: Freemium
   📖 Open Source: True
   🛠️  Tech Stack: Go, GraphQL, Python
   💻 Language Support: Python, JavaScript
   🔌 API: ✅ Available
   🔗 Integrations: LangChain, HuggingFace
   📝 Description: A cloud-native vector database with semantic search and hybrid search.

Developer Recommendations:
----------------------------------------
Weaviate and Qdrant are solid open-source options with great community support...
```

---

## 🛠️ Setup Instructions

### 1. Initialize the project

```bash
uv init .
```

### 2. Install dependencies

```bash
uv add firecrawl-py langchain langchain-openai langgraph pydantic python-dotenv
```

### 3. Set up environment variables

Create a `.env` file with your API keys:

```env
OPENAI_API_KEY=your-openai-key
FIRECRAWL_API_KEY=your-firecrawl-key
```

### 4. Run the agent

```bash
uv run main.py
```

---

## 🧾 Project Structure

```
.
├── main.py
├── .env
├── README.md
├── pyproject.toml
└── src/
    └── workflow.py
```

---

## 🔐 .gitignore

Be sure to add this to your `.gitignore`:

```
.env
.venv/
```

---

## 📜 License

MIT — use, share, and modify freely.

---

## ✨ Credits

- [LangChain](https://www.langchain.com/)
- [LangGraph](https://github.com/langchain-ai/langgraph)
- [Firecrawl](https://firecrawl.dev)
- [OpenAI](https://platform.openai.com/)
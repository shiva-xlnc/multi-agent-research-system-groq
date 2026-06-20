# 🔬 ResearchMind AI

A Multi-Agent AI Research System that automates the complete research workflow using specialized AI agents. The system searches the web, extracts relevant content, generates a structured research report, and critiques the final output for quality and completeness.

## 🌐 Live Demo

🚀 https://multi-agent-research-system-groq-kmpdaa3cfjhtrlxg9w8jdy.streamlit.app/

---

## 📸 Application Preview

![ResearchMind Home](./screenshots/home.png)

---

## ✨ Features

- 🔍 Search Agent – Finds recent and relevant information from the web
- 📄 Reader Agent – Scrapes and extracts detailed content from selected sources
- ✍️ Writer Agent – Generates a structured research report
- 🧐 Critic Agent – Reviews the report and provides feedback
- 🌐 Real-time web research using Tavily Search
- 🤖 Groq-powered LLM responses
- 🎨 Modern Streamlit UI
- 📥 Download generated reports

---

## 🏗️ System Architecture

```text
User Query
     │
     ▼
┌───────────────┐
│ Search Agent  │
└───────┬───────┘
        │
        ▼
┌───────────────┐
│ Reader Agent  │
└───────┬───────┘
        │
        ▼
┌───────────────┐
│ Writer Agent  │
└───────┬───────┘
        │
        ▼
┌───────────────┐
│ Critic Agent  │
└───────────────┘
        │
        ▼
 Final Research Report
```

---

## 🛠️ Tech Stack

### AI & LLM

- Groq
- Llama 3.3 70B
- LangChain

### Search & Data Collection

- Tavily Search API
- BeautifulSoup
- Requests

### Frontend

- Streamlit
- Custom CSS

### Backend

- Python
- LangChain Agents

---

## 📂 Project Structure

```text
ResearchMind-AI/
│
├── app.py
├── agents.py
├── tools.py
├── pipeline.py
├── requirements.txt
├── .gitignore
│
├── screenshots/
│   └── home.png
│
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/researchmind-ai.git
cd researchmind-ai
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
TAVILY_API_KEY=your_tavily_api_key
```

Run the application:

```bash
streamlit run app.py
```

---

## 🚀 Deployment

The application is deployed on Streamlit Community Cloud.

Live URL:

https://multi-agent-research-system-groq-kmpdaa3cfjhtrlxg9w8jdy.streamlit.app/

---

## 📈 Example Workflow

1. Enter a research topic
2. Search Agent gathers information
3. Reader Agent extracts detailed content
4. Writer Agent generates a comprehensive report
5. Critic Agent reviews the report
6. Download the final research report

---

## 🎯 Future Enhancements

- PDF export support
- Research history tracking
- Multi-model selection (Llama, DeepSeek, Qwen)
- Citation management
- Deep research mode
- Knowledge graph visualization

---

## 👨‍💻 Author

**Sai Shiva Varaprasad Gopu**

- LinkedIn: https://www.linkedin.com/in/sai-shiva-varaprasad/
- GitHub: https://github.com/shiva-xlnc

---

## ⭐ If you found this project useful, consider giving it a star!

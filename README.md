# Hi, I'm Reetika Srivastava 👋

*QA Automation Engineer | AI-Integrated QA | Selenium + Python | REST API Testing*

MCA graduate with a software development background and hands-on experience in manual testing, test automation, and AI-assisted QA workflows. I build end-to-end automation frameworks using Selenium WebDriver, Pytest, Postman/Newman, and Python — and I test what I build.

---

## 🛠️ Technical Skills

*Testing*
Manual Testing Functional Testing Regression Testing Smoke & Sanity API Testing Exploratory Testing UAT

*Automation*
Selenium WebDriver Pytest Page Object Model (POM) Postman Newman GitHub Actions CI/CD Data-Driven Testing

*AI / Advanced*
LangChain LangGraph RAG (Retrieval-Augmented Generation) LLM Integration Vision-Language Models Embeddings Cosine Similarity Ollama

*Languages & Tools*
Python JavaScript C# FastAPI SQLite SQL JIRA Git & GitHub

---

## 🚀 Featured Projects

### 🤖 AiQA — AI-Powered QA Automation Assistant
> *Python | FastAPI | Selenium | Pytest | LangChain | LangGraph | RAG | LLM | Qwen2.5-VL | Ollama | SQLite*

An AI-powered QA system that generates application-specific test cases by combining browser automation, RAG, LLMs, and Vision-Language models.

*How it works:*
- Accepts an application URL, feature screenshot, and QA requirement
- Inspects the live application via Selenium — extracts page text, full DOM, and compact QA-oriented DOM
- Uses RAG + cosine similarity to retrieve historically similar test cases from SQLite
- Runs a conditional LangGraph workflow: Vision Node (Qwen2.5-VL:3B) activates only when visual analysis is needed
- Generates structured test cases via LLM using both UI context and historical QA knowledge
- Exposed as a REST API via FastAPI

*Tested end-to-end with Pytest — coverage across:*
- Ollama service, AI service, RAGService (embeddings, similarity, retrieval, Vision threshold)
- QA Agent (Vision and non-Vision paths), LangGraph nodes and conditional routing
- FastAPI layer (requests, validation, file uploads, failure handling)
- External dependencies mocked for fast, deterministic unit tests

🔗 [github.com/reetika-commits/AiQA-AI-QA-Assistant](https://github.com/reetika-commits/AiQA-AI-QA-Assistant)

---

### ✈️ Flight Search Automation Framework
> *Python | Selenium WebDriver | Pytest | POM | GitHub Actions CI/CD*

End-to-end web automation framework for flight search on Yatra.

- Page Object Model for modular, maintainable structure
- Cross-browser execution — Chrome & Microsoft Edge
- Data-driven testing with external test data
- Explicit waits, assertions, and logging
- GitHub Actions CI/CD — automated test runs on every push

🔗 [github.com/reetika-commits/yatra-flight-search-automation](https://github.com/reetika-commits/yatra-flight-search-automation)

---

### ☁️ Jira Cloud REST API Automation Framework
> *Postman | Newman | Jira Cloud REST API | JavaScript | CSV Data-Driven | GitHub Actions CI/CD*

End-to-end REST API automation covering the full Jira issue lifecycle.

- Data-driven testing via CSV across Story, Bug, and Task issue types
- JavaScript scripts for response validation and dynamic variable extraction
- Environment and collection variable management
- Newman CLI execution: 3 iterations · 18 requests · 6 assertions · 0 failures
- GitHub Actions CI/CD — automated collection execution on every push

🔗 [github.com/reetika-commits/Jira-Cloud-API-Automation-Framework](https://github.com/reetika-commits/Jira-Cloud-API-Automation-Framework)

---

## 📌 Currently

🔍 Open to **QA Automation Engineer, Software Test Engineer, and SDET** opportunities — remote preferred.

📫 Connect on LinkedIn: [linkedin.com/in/reetika-srivastava-011a711b1](https://www.linkedin.com/in/reetika-srivastava-011a711b1)

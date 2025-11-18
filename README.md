# n8n AI Automations Portfolio

<div align="center">

**Intelligent automation workflows powered by AI, data pipelines, and modern web technologies**

[![GitHub stars](https://img.shields.io/github/stars/tyreefranklinjr/n8n-AI-Automations?style=social)](https://github.com/tyreefranklinjr/n8n-AI-Automations)

</div>

---

## 👋 About This Repository

Welcome to my collection of production-ready automation workflows built with **n8n**, **LangChain**, **AI/ML models**, and various APIs. This repository demonstrates my ability to architect scalable, event-driven systems that solve real-world business problems through intelligent automation.

Each workflow is:
- ✅ **Well-documented** with technical architecture details
- ✅ **Backend-focused** with emphasis on data processing and algorithms
- ✅ **Production-ready** with error handling and monitoring
- ✅ **Easily importable** into any n8n instance

---

## 🧩 Tech Stack

| Category | Technologies |
|----------|-------------|
| **Orchestration** | n8n, LangChain, Custom Workflows |
| **AI/ML** | Google Gemini, OpenAI GPT, Hugging Face Models |
| **Languages** | JavaScript, Python, SQL |
| **Data Processing** | ETL Pipelines, Web Scraping, API Integration |
| **Storage** | JSON, CSV, Database Connectors |
| **Protocols** | REST APIs, Webhooks, RSS Feeds, HTTP/HTTPS |

---

## 📁 Workflow Collection

### 1. [Market Trend Discovery Agent](./Market-Trend-Discovery-Agent/)

**Category:** Data Intelligence | Web Scraping | AI-Powered Analysis

> Automated market research system that scrapes multi-source web data, classifies user intent with Gemini LLM, and generates semantic HTML reports with deduplication algorithms.

**Key Technologies:**
- n8n workflow orchestration
- Google Gemini for natural language understanding
- Custom JavaScript nodes for data normalization
- Multi-protocol data ingestion (RSS, HTTP, APIs)

**Backend Highlights:**
- ETL pipeline architecture
- Hash-based deduplication algorithm
- Concurrent HTTP requests with exponential backoff
- Stateless design for horizontal scaling

**[View Documentation →](./Market-Trend-Discovery-Agent/README.md)**

---

### 🔜 More Workflows Coming Soon

This is part of my **30-Day Internship Challenge** where I'm building 8+ automation projects showcasing:
- Trading bot automation (TradingView API integration)
- Financial data analysis pipelines
- Customer support AI agents
- Social media analytics automation
- Real-time notification systems

---

## 🎯 What Makes These Workflows Different?

### **1. Production-Grade Engineering**
- Comprehensive error handling and retry logic
- Environment variable configuration
- Modular, maintainable node architecture
- Logging and monitoring hooks

### **2. Backend Developer Focus**
- Emphasis on data structures and algorithms
- Performance optimization considerations
- Scalability and concurrency patterns
- Clean code principles

### **3. Real Business Value**
- Solves actual pain points (not toy examples)
- Quantifiable time/cost savings
- Ready for immediate deployment
- Extensible for future requirements

---

## 🚀 Quick Start

### Prerequisites
```bash
# Self-hosted n8n (Docker)
docker run -it --rm \
  --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  n8nio/n8n
```

### Import a Workflow
1. Clone this repository:
   ```bash
   git clone https://github.com/tyreefranklinjr/n8n-AI-Automations.git
   ```

2. Navigate to your n8n instance (usually `http://localhost:5678`)

3. Go to **Workflows** → **Import from File**

4. Select the `.json` file from any workflow folder

5. Configure required credentials (API keys, webhooks, etc.)

6. Test and deploy!

---

## 📊 Project Structure

```
n8n-AI-Automations/
├── README.md                           # This file
├── Market-Trend-Discovery-Agent/
│   ├── README.md                       # Detailed documentation
│   ├── workflow.json                   # n8n workflow export
│   └── assets/                         # Diagrams, samples, etc.
├── Trading-Bot-Automation/           # (Coming soon)
├── Financial-Data-Pipeline/          # (Coming soon)
└── LICENSE
```

---

## 💼 Resume-Ready Skills Demonstrated

✅ **Backend Development:** Node.js, Python, RESTful APIs, data processing  
✅ **System Architecture:** Event-driven design, microservices, ETL pipelines  
✅ **AI/ML Integration:** LangChain, LLM prompt engineering, NLP workflows  
✅ **Data Engineering:** Web scraping, data normalization, deduplication algorithms  
✅ **DevOps Practices:** Docker, environment variables, modular configuration  
✅ **Problem Solving:** Algorithm design, performance optimization, scalability  

---

## 🎓 About Me

**Tyree Franklin Jr.**  
Computer Science Student @ UT Dallas

I'm on a 30-day intensive bootcamp to transition from student to professional software engineer. My focus areas are:
- 💻 C++ and iOS development
- 🤖 AI/ML automation and data analysis
- 📊 Trading systems and financial technology
- 🔧 Building scalable backend systems

### Connect with Me

💼 [LinkedIn](https://linkedin.com/in/tyreefranklinjr)  
📧 [Email](mailto:tyree.franklinjr@gmail.com)  
👨‍💻 [GitHub Profile](https://github.com/tyreefranklinjr)

---

## 🔄 Contributing & Feedback

This is a learning and portfolio project as part of my 30-Day Internship Challenge. Feedback, suggestions, and collaboration opportunities are always welcome!

Feel free to:
- ⭐ Star this repo if you find it useful
- 🐛 Open issues for bugs or suggestions
- 🤝 Reach out for collaboration

---

<div align="center">

**Built with ❤️ and n8n**

Part of the [30-Day Internship Challenge](https://github.com/tyreefranklinjr/2025-30-Day-Internship-Challenge)

</div>

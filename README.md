# SecureWealthTwin 🤖💼

An AI-driven personal wealth coach and financial advisor simulator built using a high-performance FastAPI microservices architecture. It integrates with Large Language Models (LLMs) via the OpenRouter API to provide automated, compliance-aware financial planning and portfolio analytics.

## 🚀 Features
- **AI Financial Chat:** Interactive advisory chat with contextual prompting powered by Llama models.
- **Financial Profiler:** Analyzes user profiles (income, savings, expenses, goals) and computes a financial health score.
- **Automated Insights:** Generates personalized saving prompts, investment guidelines, and health insights.
- **Compliance & Privacy:** Built-in simulation disclaimers, data privacy compliance, and mock KYC validation.
- **Microservices Setup:** Configured for modular deployment with support for independent wealth engines, fraud engines, and chat services.

## 🛠️ Tech Stack
- **Backend:** FastAPI, Pydantic, Python-dotenv
- **LLM Integration:** Llama (via OpenRouter API)
- **Deployment:** Docker, Docker Compose
- **Data Validation:** Pydantic schemas

## 📦 Setup & Installation
1. Clone the repository.
2. Create a `.env` file in the root folder and configure your API keys:
   ```env
   OPENROUTER_API_KEY=your-api-key-here
   ```
3. Run the application:
   ```bash
   uvicorn main:app --reload
   ```
4. Access the API documentation at `http://127.0.0.1:8000/docs`.

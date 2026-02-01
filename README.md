# GroqChain Chatbot – LLM-Powered AI Chat Application

An **AI-powered chatbot application** built using **LangChain**, **Streamlit**, and **Groq LLMs**, featuring **real-time streaming responses**, modular prompt chaining, and a production-style architecture.  
This project demonstrates practical experience in **Large Language Models (LLMs)**, **AI application development**, and **modern inference frameworks**.

---

## Project Summary

GroqChain Chatbot is a real-time conversational AI application designed to showcase hands-on skills in:
- LLM integration
- Prompt engineering
- Streaming inference
- Frontend deployment using Streamlit

The project leverages **Groq’s LPU-based inference engine** for high-speed responses and **LangChain** for clean orchestration of prompts and model outputs.

---

## Key Skills Demonstrated

- Large Language Models (LLMs)
- LangChain Framework
- Prompt Engineering
- Streaming AI Responses
- Groq LPU Inference
- Python Application Development
- Streamlit UI Development
- Session State Management
- Model Selection & Configuration
- API Integration & Security

---

## Technical Features

- **LLM Integration** using Groq-hosted LLaMA 3 models  
- **Prompt → Model → Output Parser** chaining with LangChain  
- **Real-time token streaming** for improved user experience  
- **Secure API key handling** via environment input  
- **Stateless backend with session-based memory**  
- **Modular and scalable code structure**

---

## Technology Stack

| Category | Technologies |
|--------|-------------|
| Programming Language | Python |
| LLM Framework | LangChain |
| Frontend | Streamlit |
| LLM Provider | Groq |
| Models Used | LLaMA 3.1, LLaMA 3.3 |
| Inference | Groq LPU |

---

## Application Workflow

1. User submits a query via Streamlit UI
2. LangChain formats the prompt using a system and user message template
3. Query is sent to Groq-hosted LLaMA model
4. Model response is streamed token-by-token
5. Output is parsed and rendered in real time
6. Conversation history is stored using session state

---



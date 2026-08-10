# LangGraph Learning Journey 🧠🔗

This repository documents my hands-on journey of learning **LangGraph** — a framework for building stateful, multi-step, and agentic workflows with LLMs.

I'm currently following the [CampusX LangGraph YouTube playlist](https://youtube.com/playlist?list=PLKnIA16_RmvYsvB8qkUQuJmJNuiCUJFPL&si=hKwpv6WrrSpOtwx_) and implementing every concept as a small, self-contained project as I learn it.

The goal of this repo isn't polished production code — it's to **track consistent, hands-on progress** and build a solid foundation in agentic workflow design.

---

## 📚 What I'm Learning

- Core LangGraph concepts — nodes, edges, state, and graph compilation
- Sequential and parallel (fan-out/fan-in) workflows
- State reducers for merging concurrent updates
- Conditional routing between nodes
- Structured output using Gemini API + Pydantic schemas
- (Upcoming) Agentic workflows — tool calling, ReAct, memory, human-in-the-loop

---

## ✅ Progress Tracker

| # | Topic | Status |
|---|-------|--------|
| 01 | Basics (simple & sequential graphs) | ✅ Done |
| 02 | Parallel workflows (fan-out/fan-in) | ✅ Done |
| 03 | Conditional routing | ✅ Done |
| 04 | Structured output (Gemini + Pydantic) | ✅ Done |
| 05 | Agentic workflows (tools, ReAct, memory) | 🔄 In progress |

---

## 🛠️ Tech Stack

- [LangGraph](https://github.com/langchain-ai/langgraph)
- [Google Gen AI SDK](https://github.com/googleapis/python-genai) (Gemini API)
- Pydantic (structured output schemas)
- Python 3.10+

---

## 🚀 Setup

````bash
git clone https://github.com/Abhinav-0777/LangGraph-Learning-Journey.git
cd LangGraph-Learning-Journey

python -m venv myenv
myenv\Scripts\activate      # Windows
pip install -r requirements.txt
````

---

## 📌 Note

This is a **learning-in-public** repo — code here is exploratory and will evolve as I progress through the playlist. Feedback and suggestions are welcome!

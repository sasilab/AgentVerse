# AgentVerse 🌍

**Learn AI Agents by building social impact projects.**

One agent · One framework · One real-world problem

By [@explainpannu](https://instagram.com/explainpannu) · [YouTube](https://youtube.com/@explainpannu) · [Instagram](https://instagram.com/explainpannu)

---

## Demo

![Agent thinking](./assets/terminal-demo.gif)
![Chat UI](./assets/chat-demo.gif)

---

## Episodes

| | Agent | What it does | Framework | Repo |
|---|-------|-------------|-----------|------|
| 🌤️ | **BreezyBuddy** | Nudges you to go outside based on weather | Pure Python | [→ repo](https://github.com/sasilab/BreezyBuddy) |
| 🎭 | **Tamil Meme Crew** | Roasts your city's weather + pollution in sarcastic Tanglish | CrewAI | [→ repo](https://github.com/sasilab/AgentVerse-CrewAI-Tamil-Meme) |
| 🥗 | **Diet Memory Agent** | Personalized diet tips that learn your taste via 👍👎 feedback | LangGraph + Mem0 | [→ repo](https://github.com/sasilab/diet_memory_agent) |
| 📄 | **PDF Nutrition RAG** | Upload a food chart, get tips with real data — Normal vs Agentic RAG | LangGraph + ChromaDB | [→ repo](https://github.com/sasilab/rag_nutrition_agent) |
🌐 **Shared frontend** — one PWA for all episodes → [AgentVerse-Frontend](https://github.com/sasilab/AgentVerse-Frontend)

```
                    +---------------------------+
                    |      Frontend PWA          |
                    |   chat - notifications     |
                    |   settings - BYOK          |
                    +-------------+-------------+
                                  |
                       POST /api/run {city}
                                  |
               +------------------+------------------+------------------+
               |                  |                  |                  |
               v                  v                  v                  v
        +-----------+      +-----------+      +-----------+      +-----------+
        | BreezyBuddy|      | Tamil Meme|      | Diet Agent|      | PDF RAG   |
        |  EP00      |      |  EP01     |      |  EP02     |      |  EP03     |
        +-----------+      +-----------+      +-----------+      +-----------+
                              ...
                  (new episodes plug in here)
```

## Why this exists

- Each agent solves a **real problem**, not a toy demo
- **Zero paid APIs** for data — Open-Meteo, free and open
- **BYOK** — Groq (free) / Gemini / OpenAI / Ollama
- **One frontend, many backends** — learn the framework, not the UI
- Every episode **built live with Claude Code**

---

## Get started

```bash
git clone https://github.com/sasilab/AgentVerse-CrewAI-Tamil-Meme.git
# follow the README inside
```

---

MIT · [@explainpannu](https://instagram.com/explainpannu)

> *"Learn the pattern. Then every framework is just syntax."*

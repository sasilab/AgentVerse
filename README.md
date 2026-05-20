# AgentVerse

**Learn AI Agents by building social impact projects.**

Each episode teaches a different agent framework by solving a real-world problem. Same pattern, different tools — so you learn the *concept*, not just the code.

By [@explainpannu](https://instagram.com/explainpannu) · [YouTube](https://youtube.com/@explainpannu) · [Instagram](https://instagram.com/explainpannu)

---

## The pattern

Every agent follows 5 ingredients:

```
👀 Eyes    → Data source (API, sensors, datasets)
🧠 Brain   → LLM (Gemini, GPT, Claude, Groq, Ollama)
📝 Memory  → Context (history, preferences)
⚙️ Loop    → Decision engine (ReAct, orchestration)
📲 Action  → Output (alerts, advice, notifications)
```

---

## Episodes

| # | Agent | Problem | Framework | Status | Repo |
|---|-------|---------|-----------|--------|------|
| 00 | **BreezyBuddy** | Weather nudge | Pure Python + ReAct | ✅ Live | [sasilab/BreezyBuddy](https://github.com/sasilab/BreezyBuddy) |
| 01 | **Tamil Meme Crew** | Pollution + weather → Tanglish roast | CrewAI | ✅ Live | [sasilab/AgentVerse-CrewAI-Tamil-Meme](https://github.com/sasilab/AgentVerse-CrewAI-Tamil-Meme) |
| 02 | *Coming soon* | New problem | New framework | 🔜 Next | — |

---

## Shared frontend

One PWA frontend that works across all episodes. WhatsApp-style chat, push notifications, settings panel, BYOK.

**→ [sasilab/AgentVerse-Frontend](https://github.com/sasilab/AgentVerse-Frontend)**

```
┌──────────────────────────────┐
│    AgentVerse Frontend PWA    │  ← same for ALL episodes
│  Chat UI + Push Notifications │
│  POST /api/run {city: "..."}  │
└──────────────┬───────────────┘
               │
    ┌──────────┼──────────┐
    ▼          ▼          ▼
 CrewAI    LangGraph    Google
 (EP01)    (EP02?)     ADK (EP03?)
```

---

## What makes this different

- **Social impact** — not another todo app. Each agent solves a real problem.
- **Zero paid APIs for data** — all data from free, open APIs (Open-Meteo, etc.)
- **BYOK (Bring Your Own Key)** — Groq (free), Gemini (free tier), OpenAI, or Ollama (local). Your choice.
- **One frontend, many backends** — learn the framework, not the UI.
- **Built live with Claude Code** — every episode is built from scratch in a terminal session.

---

## Quick start

Pick an episode, clone it, follow its README:

```bash
# Episode 01: CrewAI Tamil Meme Crew
git clone https://github.com/sasilab/AgentVerse-CrewAI-Tamil-Meme.git
cd AgentVerse-CrewAI-Tamil-Meme
# follow the README inside

# The shared frontend (needed for the PWA)
git clone https://github.com/sasilab/AgentVerse-Frontend.git
```

---

## This project is open-ended

- Frameworks list grows as new ones emerge
- Problems list grows as new ideas come up
- Nothing is locked — everything evolves

**Want to see a specific framework or problem?** Open an issue or DM [@explainpannu](https://instagram.com/explainpannu).

---

## License

MIT — use it, learn from it, teach with it.

> *"Don't just learn one framework. Learn the pattern. Then every framework is just syntax."*

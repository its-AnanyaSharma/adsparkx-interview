# Persona-Adaptive Customer Support Agent 

A smart AI-powered customer support agent that dynamically detects customer persona, retrieves relevant knowledge base (KB) content, adapts its response tone accordingly, asks intelligent follow-up questions, and escalates critical issues to human support with full context handoff.

---

##  Problem Statement

Build an intelligent support agent that:

- Detects customer persona (Technical Expert, Frustrated User, Business Executive, General User)
- Retrieves the most relevant knowledge base (KB) article
- Adapts response tone based on persona
- Asks intelligent follow-up questions (one at a time)
- Escalates to a human agent when required with complete context handoff

---

##  Key Features

-  Persona Detection using rule-based NLP
-  Intent Detection (login, payment, API, refund, etc.)
-  Multi-turn Follow-up Question Flow
-  Knowledge Base (KB) Retrieval using intent + text similarity
-  Persona-based Tone Adaptation
-  Intelligent Escalation Engine with Severity Levels
-  Context Handoff for Human Support
-  REST API Backend with React Frontend

---

##  Supported Personas

- **Technical Expert** – receives concise, technical responses
- **Frustrated User** – receives empathetic and reassuring responses
- **Business Executive** – receives impact-focused summaries
- **General User** – receives clear, friendly guidance

---

## 🛠 Tech Stack

### Frontend:
- React (Vite)
- JavaScript
- CSS (Inline Styling)

### Backend:
- Node.js
- Express.js
- Nodemon
- CORS

### AI Logic:
- Rule-based NLP
- Intent Detection Engine
- Persona Classification Module
- Escalation Decision Engine
- Knowledge Base Retrieval System

---

##  Project Structure

```txt
persona-support-agent/
│
├── backend/
│   ├── index.js
│   ├── kb.js
│   ├── persona.js
│   ├── intent.js
│   ├── escalation.js
│   ├── utils.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── index.html
│   └── package.json
│
└── README.md

d6" />


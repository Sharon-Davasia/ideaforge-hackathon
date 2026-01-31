# Ideaforge-(Dev AI Demystified Hackathon)
AI-powered idea-to-project pipeline using IBM watsonx Orchestrate

# 🚀 IdeaForge - AI-Powered Idea-to-MVP Pipeline

## IBM Dev Day AI Demystified Hackathon 2026

Transform raw ideas into complete, deployment-ready project packages in minutes using multi-agent AI orchestration.

---

## 🎯 Problem Statement

Teams spend 10-20+ hours on project planning before any real work begins:
- Manual idea validation
- Spreadsheet-based project planning
- Whiteboard architecture sessions
- Documentation written from scratch

**IdeaForge compresses this into a single conversation.**

---

## 💡 Solution

IdeaForge is a multi-agent AI system built on **IBM watsonx Orchestrate** that transforms natural language ideas into complete project kickoff packages.

### How It Works

User describes idea
↓
┌─────────────────────────────┐
│ IdeaForge Orchestrator │
│ (Primary Coordinator) │
└──────────────┬──────────────┘
│
┌──────────┼──────────┬──────────┐
↓ ↓ ↓ ↓
┌────────┐ ┌────────┐ ┌────────┐ ┌────────┐
│ Idea │ │Project │ │ Tech │ │ Docs │
│Validator│ │Planner │ │Architect│ │Generator│
└────────┘ └────────┘ └────────┘ └────────┘
↓ ↓ ↓ ↓
└──────────┴──────────┴──────────┘
↓
Complete Project Package


---

## 🤖 Agents

| Agent | Purpose | Model |
|-------|---------|-------|
| **IdeaForge Orchestrator** | Coordinates all agents, synthesizes outputs | IBM Granite 3-8b |
| **Idea Validator** | Feasibility analysis, market scoring, GO/NO-GO | IBM Granite 3-8b |
| **Project Planner** | Timeline, phases, milestones, resource planning | IBM Granite 3-8b |
| **Tech Architect** | Technology stack, system design, APIs | IBM Granite 3-8b |
| **Docs Generator** | PRD, user stories, sprint tasks | IBM Granite 3-8b |

---

## 📦 Output Package Includes

- ✅ Feasibility scores (Market, Technical, Competitive)
- ✅ GO/NO-GO recommendation with confidence %
- ✅ Risk analysis with mitigations
- ✅ Phase-based project timeline
- ✅ Resource requirements
- ✅ Complete technical architecture
- ✅ Technology stack recommendations
- ✅ Product Requirements Document (PRD)
- ✅ User stories with acceptance criteria
- ✅ Sprint 1 task breakdown

---

## 🛠️ Built With

- **IBM watsonx Orchestrate** - Multi-agent orchestration platform
- **IBM Granite 3-8b-instruct** - Foundation model for all agents
- **No-code agent builder** - Visual agent configuration
- **Knowledge bases** - Custom validation criteria and templates

---

## 📸 Screenshots

### Agent Architecture
![Agent List](screenshots/agent-list.png)

### Sample Output
![Sample Output](screenshots/sample-output.png)

---

## 📹 Demo Video

[Watch the demo] https://drive.google.com/file/d/1rimo_MH1JKuaS2Tu2hmJn0Ay3Mrofqi9/view?usp=drivesdk

---

## 👥 Team

- [Sharon K Davasia]

---

## 🏆 Hackathon Theme

**"AI Demystified — From Idea to Deployment"**

IdeaForge embodies this theme by making AI approachable and practical, transforming complex multi-step planning into a simple conversation.

---

### Built with ❤️ using IBM watsonx Orchestrate

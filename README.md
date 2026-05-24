# CodeForge

An AI-powered coding assistant that uses multi-agent collaboration to generate, review, test, and refine code through a structured development workflow.

## Overview

CodeForge replaces traditional single-step code generation with a coordinated AI workflow powered by LangChain.js and Vertex AI. Instead of relying on one model response, specialized planner, coder, reviewer, and tester agents collaborate to produce more reliable and higher-quality code outputs. The platform supports persistent conversational memory using Firestore and is deployed on Google Cloud Run to handle scalable concurrent executions.

## Features

- 🤖 **Multi-agent architecture** — Planner, coder, reviewer, and tester agents collaborate to generate higher-quality code
- 🧠 **Persistent agent memory** — Firestore stores conversational and workflow context across sessions
- ⚡ **Structured code generation** — LangChain.js orchestrates multi-step reasoning instead of single-response outputs
- 🔍 **Automated code review** — Reviewer agents validate correctness, readability, and best practices
- 🧪 **Integrated testing workflow** — Tester agents simulate validation and detect potential issues before delivery
- ☁️ **Scalable cloud deployment** — Cloud Run deployment supports 100+ concurrent executions
- 💬 **Interactive developer experience** — React frontend enables real-time AI-assisted coding workflows

## Tech Stack

- **Backend:** Node.js, LangChain.js
- **Frontend:** React
- **AI:** Vertex AI
- **Database:** Firestore
- **Cloud:** Google Cloud Platform (GCP)
- **Deployment:** Cloud Run

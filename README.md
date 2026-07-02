# Hi, I'm Jinseok Lee 👋

**AI Platform / Backend Engineer** passionate about building production-ready AI systems, LLM platforms, workflow automation, and developer tooling.

I enjoy solving engineering problems by understanding systems internally rather than treating frameworks as black boxes.

Most of my work focuses on designing AI platforms, integrating LLMs into production services, building automation that removes repetitive work, and creating backend architectures that remain maintainable as products evolve.

---

# What I'm Working On

Currently interested in:

* AI Platform Engineering
* Multi-Agent Systems
* LangGraph & LangChain
* Amazon Bedrock
* LLM Infrastructure
* AI Workflow Orchestration
* Developer Tooling
* QA Automation
* Production AI Systems

---

# Professional Experience

Over the past few years, I've been building and operating AI-powered services used in production.

### AI Platform

* Designed and developed user-facing AI services powered by GPT and Claude.
* Built internal AI platforms integrated with administration systems.
* Implemented prompt engineering and AI workflow optimization.
* Developed backend services for AI APIs and production workloads.
* Refactored AI infrastructure to improve maintainability and operational stability.

---

### Speech AI

Built production speech evaluation services using Azure Speech.

Responsibilities included:

* Pronunciation assessment
* Speaking evaluation
* AI-generated feedback
* Serverless backend architecture with AWS Lambda

---

### AI Automation

Designed automation systems to reduce engineering effort.

Examples include:

* AI-powered PDF parsing
* Internal MCP Server development
* Developer workflow automation
* AI-assisted operational tooling

---

### QA Automation

Built prompt-driven QA systems capable of validating complete service flows.

Coverage:

* Browser Automation (Playwright)
* API Validation
* Database Verification
* End-to-end Regression Testing

---

### Backend Engineering

Daily technologies:

* PHP / Laravel
* Python / FastAPI
* Node.js
* REST API
* AWS Lambda
* PostgreSQL
* MySQL

I prefer designing backend systems with clear boundaries between controllers, services, workflows, and infrastructure to keep them maintainable over time.

---

# Open Source Contributions

One of my favorite ways to learn is reading framework source code.

Rather than stopping at "it doesn't work", I enjoy understanding *why* it behaves that way.

### LangChain AWS

While integrating Amazon Bedrock Application Inference Profiles with Claude Sonnet 5, I discovered that `langchain-aws` silently disabled streaming because of an outdated client-side allowlist.

I:

* Reproduced the issue across multiple versions
* Compared direct model invocation with Application Inference Profiles
* Traced the execution flow inside `ChatBedrockConverse`
* Identified the incorrect streaming capability validation
* Proposed a future-proof fix
* Documented a temporary workaround

The issue was acknowledged by the LangChain maintainers and accepted for resolution.

Issue:
https://github.com/langchain-ai/langchain-aws/issues/1139

I believe understanding framework internals is just as valuable as using their public APIs.

---

# Tech Stack

```text
Languages
PHP • Python • JavaScript • TypeScript • SQL

Backend
Laravel
FastAPI
Node.js
REST API

AI / LLM
LangGraph
LangChain
OpenAI GPT
Claude
Amazon Bedrock
Prompt Engineering
RAG
AI Agents

Automation
Playwright
Browser Automation
API Testing
Database Validation

Cloud
AWS Lambda
Docker
AWS SSM Parameter Store

Speech
Azure Speech

Database
PostgreSQL
MySQL
```

---

# Engineering Principles

Some principles I consistently follow:

* Build platforms, not one-off features.
* Understand framework internals before applying workarounds.
* Prefer maintainability over clever implementations.
* Keep orchestration explicit and observable.
* Separate business logic from AI orchestration.
* Automate repetitive operational tasks.
* Design systems that remain understandable months later.

---

# GitHub

Most repositories here are experiments, production-inspired prototypes, or tools exploring AI platform engineering, workflow automation, and backend architecture.

Feel free to explore the code or reach out if you'd like to discuss AI systems, LangGraph, automation, or backend engineering.

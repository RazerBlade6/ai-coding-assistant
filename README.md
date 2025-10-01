# Development Plan

## Project Overview

### Goal

Build an AI assistant that suggest code completions, answers coding questions, and edits or generates contextually as a VSCode extension

Particularly ironic for me as I don't use AI assistants or VSCode.

### Code Features

Intelligent autocompletion, context-aware chat, code refactoring, real-time editing, search/retrieval of project knowledge, natural language code queries.

## Technologies

- **Language Models:** Open-source code LLMs (CodeLlama, Gemma)
- **Orchestration & Agents:** LangChain or DSPy
- **NLP Libraries:** HuggingFace Transormers
- **Indexing & Retrieval:** LlamaIndex or Chroma DB
- **Backend Framework:** Flask
- **Frontend Framework:** VSCode extension, maybe a bespoke weeb interface too? Not sure atm
- **Deployment:** Probably GCP w/ Docker, Kubernetes

## Plan

Phase | Tasks | Time Estimate|
| :-- | :---- |:--|
| Planning & Scoping | Define Scope, collect requirements, survey LLMs | Done|
| Backend & Model Integration | Integrate|
| Context, Retrieval Systems | embed codebase, build semantic search | 2 weeks|
| Orchestration | LangChain agent implementation | 2 weeks |
| Frontend | Build VSCode extension | 2 weeks |
| Testing + Deployment | Standard DevOps stuff | 2 weeks |

---
title: "Knowledge Base Q&A Application"
excerpt: "Desktop app for managing a personal knowledge base, with hybrid retrieval and LLM-powered, citation-grounded Q&A.
[(Repo Link)](https://github.com/kuldeep7688/QA_app_dev_with_harness)<br>"
collection: projects
---

## Description
A desktop knowledge base application built with Electron, React, TypeScript, and SQLite. Imported text and Markdown documents are indexed with hybrid retrieval (BM25 full-text search combined with local vector embeddings via `all-MiniLM-L6-v2`), and session-based Q&A is powered by NVIDIA NIM's language model with answers grounded in document citations. Also includes web search integration via the Tavily API, file upload for chat context, streaming answer generation with Markdown rendering, and feedback collection.

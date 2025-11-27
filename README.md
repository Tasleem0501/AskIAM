# AI IAM Assistant (POC)

This project is a Proof of Concept (POC) for an AI-powered Identity and Access Management (IAM) assistant.  
The system helps users understand access roles, choose a role, and automatically generate an access request ticket.

---

## Project Overview

The IAM Assistant allows users to:

1. Ask for access or describe what they need.
2. Get recommended roles using vector search and an LLM.
3. Select a role from the suggestions.
4. Automatically generate an access request ticket (mock or ServiceNow).
5. Track the status of the ticket.

The backend uses FastAPI, PostgreSQL, pgvector, and embeddings.

---
## Datasets

This project includes three datasets stored in the `data/` folder:

- users.csv
- roles.csv
- applications.csv
  
## Tech Stack

- Python  
- FastAPI  
- PostgreSQL  
- pgvector  
- Embeddings (OpenAI or local)
  
## Architecture Summary


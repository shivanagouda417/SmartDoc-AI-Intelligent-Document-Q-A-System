# SmartDoc-AI-Intelligent-Document-Q-A-System
Build a GenAI-powered assistant where users upload documents and ask questions in natural language

🔹 Project Name

SmartDoc AI – Intelligent Document Q&A System

🔹 Problem Statement

Banks and enterprises have thousands of PDFs (policies, KYC rules, loan documents, compliance manuals).
Employees waste time searching manually.

👉 Build a GenAI-powered assistant where users upload documents and ask questions in natural language.

Example:

“What is the minimum CIBIL score required for home loan?”

“What is the penalty for late EMI?”

AI reads the documents and gives accurate answers.

🏗️ System Architecture (High Level)
User → Frontend → Spring Boot API → OpenAI / LLM
                               ↓
                        Vector Database
                               ↓
                           Document Store

🛠 Tech Stack (Java Friendly)

Java 17+

Spring Boot

Spring AI (recommended)

OpenAI API or Azure OpenAI

PostgreSQL + pgvector (or Pinecone)

React (optional frontend)

Docker

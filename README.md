# AI-bot

Company Research Assistant (Account Plan Generator)
🧠 Project Overview

The Company Research Assistant is an AI-powered conversational agent built using Chatbase. It helps users research companies through natural conversation and automatically generates structured, actionable Account Plans.

The agent adapts to different user personas, detects conflicting information, supports section-level editing, and provides clear research updates.
This project demonstrates conversational intelligence, agentic behaviour, reasoning abilities, and structured plan generation.

🎯 Key Features
✔ 1. Smart Company Research

The agent gathers information using:

Public company knowledge

Logical inference

Uploaded training files

Company datasets

Investor reports and templates

It synthesizes insights into clean, business-ready sections.

✔ 2. Structured Account Plan Generation

The agent produces a professional account plan with the exact format:

Company Overview

Products & Services

Financial Summary

Key Decision Makers

Competitors

Market Position

Buying Signals

Risks & Challenges

Opportunities

Recommended Next Steps

✔ 3. Handles Multiple User Personas

The agent intelligently recognizes the type of user:

Confused User → asks clarifying questions

Efficient User → gives short, precise answers

Chatty User → stays polite but redirects to the goal

Edge-case User → safely refuses private or confidential requests

✔ 4. Conflict Detection

When conflicting data appears (e.g., multiple revenue values), the bot:

Identifies contradictions

Shows the conflicting values

States the source types

Asks how the user wants to proceed

✔ 5. Section-Level Editing

The user can update any specific section:

Example:

Update the Opportunities section for Apple.


The agent modifies only that section, maintaining the rest of the plan.

✔ 6. Safe, Professional, and Ethical

The agent will NOT provide:

Personal emails

Personal phone numbers

Confidential internal data

Private financials

It only uses publicly known or user-supplied data.


🏗️ Architecture Overview

User (Chat / Voice)
        │
        ▼
Chatbase AI Agent
   ├── System Prompt
   ├── Training Data (Files, Text, Q&A)
   ├── Website Sources
        │
        ▼
Information Extraction
   ├── PDFs (Annual Reports, Presentations)
   ├── Company Data CSVs
   ├── Manual Training Text
        │
        ▼
Research Reasoning Engine
   ├── Conflict Detection
   ├── Persona Handling
   ├── Clarifying Questions
        │
        ▼
Account Plan Generator
   ├── Structured Template
   ├── Section Editing
        │
        ▼
Final Output to User


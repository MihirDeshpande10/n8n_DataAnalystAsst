# n8n_DataAnalystAsst

Data Analyst Assistant – n8n Workflow
Overview

This project implements a Data Analyst Assistant using n8n, designed to convert plain-English business questions into structured, actionable insights and deliver them automatically via email.

The goal is to demonstrate how analytics can move beyond dashboards into conversational and automated insight delivery.

Workflow Description

The workflow is triggered by a chat message and follows a linear, automated analytics process:

Chat Trigger

User submits a natural language analytics question.

AI Agent

Interprets analytical intent.

Determines required metrics and aggregations.

Data Access

Reads structured data from Google Sheets.

Context Handling

Uses a memory node to retain conversational and analytical context.

Insight Generation

Computes high-level metrics (e.g., revenue, cost, profit, rankings).

Insight Delivery

Sends summarized insights directly to the user via Gmail.

Key Capabilities

Natural language → analytics translation

Automated metric computation

Context-aware responses

Email-based insight delivery

No manual dashboard interaction required

Tech Stack

n8n – Workflow orchestration

AI Agent (LLM-powered) – Intent understanding & reasoning

Google Sheets – Structured data source

Memory Node – Context persistence

Gmail Integration – Automated insight delivery

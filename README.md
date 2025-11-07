# 🤖 AI Automation Workflows (n8n)

This repository contains three automation workflows built using **n8n** to manage communication, scheduling, and follow-up processes through calls, messages, and AI assistance.

---

## ⚙️ Overview

These workflows combine **Retell AI**, **OpenAI**, and **LeadConnector APIs** to automate routine tasks such as calling leads, handling conversations, scheduling appointments, and sending follow-up messages — all with minimal human input.

---

## 🧩 Included Workflows

### 1️⃣ Master AI Agent
A smart AI assistant that processes inbound or outbound call data and interacts naturally with users.  
It can understand intent (like checking availability or booking appointments), use AI reasoning to decide what to do next, and record or update relevant information automatically.

---

### 2️⃣ Trigger the Call
This workflow automatically initiates a call through **Retell AI**.  
It takes user or lead information, formats it properly, and connects the AI agent to make the call.  
It’s mainly used to start automated outreach or follow-up calls.

---

### 3️⃣ Trigger SMS + Follow-up
Handles the SMS part of the communication.  
It sends an initial message to a contact, checks if they respond, and if not, sends follow-up messages intelligently after a set delay or during working hours.

---

## 🧠 Highlights
- Built entirely in **n8n** with modular workflows.
- Integrates APIs like **Retell AI**, **OpenAI**, and **LeadConnector**.
- Automates communication across calls and SMS.
- Reduces manual work and improves response handling efficiency.

---

## 🚀 Purpose
These workflows are designed to demonstrate how AI and automation can simplify real-world operations such as:
- Customer reactivation
- Appointment scheduling
- Lead engagement and follow-up

---

## 🧩 Tech Stack
- **n8n** – Workflow automation platform  
- **OpenAI API** – For intelligent conversation logic  
- **Retell AI** – For automated voice interactions  
- **LeadConnector API** – For CRM and message handling  

---

## 📂 Files
- `Master AI Agent.json`
- `Trigger the Call.json`
- `Trigger SMS + Followup.json`

Each file can be imported directly into your n8n instance to explore or modify the workflows.

---

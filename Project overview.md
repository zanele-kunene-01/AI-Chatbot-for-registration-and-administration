# University Chatbot for Registration and Administrative Support

## Project Overview
This project is an AI-powered WhatsApp chatbot designed to support students at South African Universities of Technology. It helps with registration processes, fee queries, document uploads, and general administrative support. 

## Features
- Answer FAQs on fees,registration, residence administration deadlines,, and documents
- Guide students through registration steps-provide a registration buddy
- Support multilingual queries (English, isiXhosa, Afrikaans)
- Escalate complex cases to human staff
- 24/7 availability on WhatsApp

## 🛠️ Tech Stack
- **Language:** Python
- **AI/NLP Framework:** Rasa / spaCy / Transformers
- **Integration:** WhatsApp Business Cloud API (Meta)
- **Database:** PostgreSQL + Redis
- **Deployment:** Hosted on Render (Free Tier), connected to WhatsApp via Cloud API


## 📂 Repository Structure
- `docs/` : Design documents and diagrams
- `data/` : Training data for chatbot
- `src/` : Source code (bot logic, NLP, integrations)
- `tests/` : Automated tests
- `requirements.txt` : Project dependencies

## 🔗 WhatsApp Integration
This chatbot uses **Twilio WhatsApp API** for development and will be migrated to the **Meta WhatsApp Business Cloud API** for production.

---

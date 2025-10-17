# MediBot-
AI Health Assistance For Communities 

Deployment links(https://claude.ai/public/artifacts/6021d3f6-5847-44b9-9eef-0d88daf9105e) 

Pitch deck link(https://www.canva.com/design/DAG19fdmnrA/fBMbnM0tAv91S-GcjX6d4g/view?utm_content=DAG19fdmnrA&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h448b52c564) 

GitHub link:  https://github.com/John36-collab


🩺 AI-Driven Health Assistant for Communities

Focus Area: Good Health and Well-being

📌 Objective

The project aims to provide accessible and basic health support through an AI-powered assistant. It focuses on early awareness, self-care, and preventive measures by guiding users to check symptoms, access health resources, and receive wellness reminders.

The structure of the system is designed to be interactive, modular, and scalable, making it suitable for both individual use and community-level deployment.


---

🧠 Core Features

1. Symptom Checker

Uses structured logic or machine learning to interpret user inputs.

Accepts basic text or voice inputs and maps them to common health conditions.

The output is structured as guidance or recommendation (not diagnosis).

Ensures clarity and accessibility for non-experts.


2. Health Tips Engine

Provides personalized wellness information.

The structure relies on demographic inputs such as age, gender, or location to tailor health tips.

Encourages preventive actions like vaccinations, hygiene practices, or lifestyle improvements.


3. Reminders and Scheduling

Handles appointment or medication reminders in a simple structured format.

Allows users to set reminder parameters like time, date, and frequency.

Designed to support multilingual reminders and easy modification or cancellation.


4. Mental Health Check-in Chatbot

Provides emotional support through structured conversations.

Uses empathetic language models and mental well-being prompts.

Helps users self-reflect and get guidance or resource links when needed.



---

🧰 Tech Stack Overview

Backend: Node.js

Provides the core structure for API endpoints, user authentication, and integration handling.

Acts as the communication bridge between the AI engine, database, and frontend or chat interface.


Conversational Interface: Rasa

Handles intent classification and response generation.

Follows a structured flow: User Input → NLU Processing → Intent Recognition → Response/Action.


Database: Supabase

Stores user profiles, symptom check logs, reminder schedules, and mental health entries.

The structure allows for secure and organized data management.


Integration Layer: WhatsApp

Provides a simple and familiar interface for users to interact with the assistant.

Message structure is optimized for short, clear prompts and quick actions.




---

🧭 System Flow Structure

1. User Interaction Layer

WhatsApp chat interface receives user messages.

Messages are processed through the conversational AI layer.



2. Processing Layer

Rasa identifies the intent and triggers the correct response structure.

Node.js coordinates API calls and data retrieval from Supabase.



3. Output Layer

Response is returned in structured, simple, and actionable language.

Optional follow-up actions (like reminders or health tips) are scheduled.





---

🌍 Impact

Access: Expands health information access to communities with limited medical facilities.

Awareness: Encourages early symptom checking and promotes healthy habits.

Support: Provides a preventive care model that eases pressure on traditional health systems.

Mental Well-being: Encourages conversations around emotional health in a safe, private space.



---

🏗️ Suggested Project Structure

AI-Driven-Health-Assistant/
│
├── docs/                    # Documentation & design notes
├── src/
│   ├── backend/             # Node.js logic and server endpoints
│   ├── rasa_bot/            # Conversational AI training files & intents
│   └── integrations/        # WhatsApp and external service connectors
│
├── database/
│   └── supabase/            # Schema, tables, and API connection structure
│
├── config/                  # Environment variables and credentials
├── assets/                  # Icons, UI designs, or health illustrations
└── README.md                # Project documentation

This structure ensures clarity, maintainability, and modularity — allowing different features to be developed and scaled independently.


---

🧑‍🤝‍🧑 Future Enhancements

Support for multiple languages for wider reach.

Integration with local health facilities or NGOs.

Voice interface for users with low literacy levels.

Advanced analytics for community health trends.



---

📝 Note

This project is intended for educational and awareness purposes only. It does not replace professional medical consultation.


---

Contributors and Community Support Welcome 💙
Your ideas, design improvements, and feedback help make this health assistant more impactful for communities worldwide.


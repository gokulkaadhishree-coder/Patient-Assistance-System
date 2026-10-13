# 🏥 Patient Assistance System

An AI-powered patient assistance solution built using **UiPath Agentic AI and Maestro** to streamline patient intake, symptom severity assessment, doctor approval, and patient email communication.

## 📌 Overview

The Patient Assistance System combines AI agents, workflow automation, and human-in-the-loop approval to manage the initial stages of patient assistance. It analyzes reported symptoms against a reference dataset, recommends an appropriate next action, and supports doctor review before communicating with patients.

## ✨ Key Features

- **AI-Powered Severity Analysis:** Evaluates patient symptoms and their duration against a reference dataset to classify severity and suggest an appropriate next action.
- **Patient Query Assistance:** Uses an AI agent to support patient queries.
- **Doctor Approval Workflow:** Provides a dedicated approval interface for reviewing and approving or rejecting patient-related actions.
- **Automated Email Generation:** Generates patient-facing email content based on the provided patient information, severity, and approved action.
- **Email Automation:** Supports automated email communication through a dedicated UiPath workflow.
- **Process Orchestration:** Uses UiPath Maestro to coordinate agents, workflows, and approval tasks.
- **Human-in-the-Loop (HITL):** Includes human review to help ensure important decisions are checked before proceeding.

## 🛠️ Tech Stack

- **UiPath Studio Web** — Workflow and solution development
- **UiPath Agentic AI** — AI-powered symptom analysis and query assistance
- **UiPath Maestro** — Process orchestration
- **UiPath Apps** — Doctor approval interface
- **UiPath Integration Service** — Integration with connected services
- **Reference Dataset** — Symptom and severity information used for assessment

## 🔄 Workflow

1. **Patient Intake:** Collect patient information, including name, age, gender, email, symptoms, and symptom duration.
2. **Severity Assessment:** The Severity Analysis Agent compares the reported symptoms with the reference dataset.
3. **Recommended Action:** The agent returns a severity classification and a suggested next action.
4. **Doctor Review:** The workflow routes the case for human approval or rejection.
5. **Email Generation:** The Email Generation Agent prepares patient communication using the supplied details and action.
6. **Email Delivery:** The email workflow handles the communication process.
7. **Orchestration:** UiPath Maestro coordinates the overall workflow and its participating components.

## 🧩 Main Components

| Component | Purpose |
|---|---|
| Severity Analysis Agent | Assesses symptoms and determines a severity category and recommended action |
| Query Assistance Agent | Assists with patient queries |
| Email Generation Agent | Generates patient-facing email content |
| Doctor Approval | Supports human review and approval or rejection |
| Send Email | Handles email communication |
| Maestro BPMN | Coordinates the overall process |

## 🎯 Project Objective

The objective is to demonstrate how Agentic AI, process orchestration, and human oversight can work together to improve the efficiency and consistency of patient assistance workflows.

## ⚠️ Disclaimer

This project is intended for educational and demonstration purposes. It is **not a substitute for professional medical advice, diagnosis, or treatment**. AI-generated severity assessments and recommended actions must be reviewed by qualified healthcare professionals. Critical or emergency symptoms require immediate medical attention.

## 🚀 Future Enhancements

- Integrate secure electronic health record systems.
- Add appointment scheduling and follow-up reminders.
- Improve patient query handling with verified medical knowledge sources.
- Introduce audit logs and role-based access controls.
- Add multilingual patient communication.
- Strengthen data privacy and security controls.

## 👩‍💻 Project Type

**Domain:** Healthcare Automation  
**Technologies:** Agentic AI, RPA, Workflow Orchestration  
**Platform:** UiPath


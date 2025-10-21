# AgentToyota — Smart Vehicle Financing AI Agent

## Overview
AgentToyota is an intelligent web application that helps customers find personalized Toyota financing and leasing options based on their income, credit score, and lifestyle preferences.  
It is built using **FastAPI (Python)** for the backend and **React** for the frontend, with **SQLite** for data storage.  
The system generates instant financing simulations, model recommendations, and personalized insights powered by **LLM reasoning** (Gemini or Groq LLaMA).  

---

## Key Features
- Smart Financing Agent that suggests optimal financing and leasing plans.  
- Personalized EMI simulations based on salary, credit score, and preferences.  
- Model recommendations that align with user budgets and lifestyles.  
- Secure sign-up and login system using FastAPI, SQLite, and UUIDs.  
- Dashboard for viewing plan comparisons and payment timelines.  
- Toyota-themed user interface with clean, minimal design.

---

## Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React, TailwindCSS, Axios |
| Backend | FastAPI (Python), Uvicorn |
| Database | SQLite |
| AI Integration | Gemini API / Groq LLaMA |
| Hosting | Localhost / Render / Vercel |
| Version Control | Git & GitHub |

---

## Project Structure

AgentToyota/
├── backend/
│   ├── main.py               # FastAPI routes
│   ├── models.py             # SQLite schema
│   ├── database.py           # DB connection
│   ├── auth.py               # Login/Signup logic with UUID
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── App.js            # Main React app
│   │   ├── components/       # UI components
│   │   └── pages/            # Signup, Login, Dashboard
│   ├── package.json
│   └── tailwind.config.js
│
└── README.md

---

## How to Run Locally

### Backend Setup
```bash
cd backend
python3 -m venv venv
source venv/bin/activate   # For Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload


Backend runs on: http://127.0.0.1:8000

Frontend Setup


cd frontend
npm install
npm run dev



⸻

AI Agent Logic

The Finance Agent uses:
	•	Credit score thresholds to calculate APR and loan tenure.
	•	Income segmentation to classify users into categories.
	•	Gemini or LLaMA model for reasoning and conversational explanations.
	•	Optional ElevenLabs integration for voice output.

⸻

Unique Highlights
	•	Focuses on financial literacy instead of simple chatbot interaction.
	•	Combines AI reasoning with visual financial simulations.
	•	Toyota-themed design emphasizing trust and clarity.
	•	Integration of both data-driven logic and LLM-based explanation.

⸻

Future Enhancements
	•	Integrate real Toyota Financial Services APIs.
	•	Add credit history tracking and personalized improvement tips.
	•	Deploy to AWS or Render for production scalability.
	•	Add mobile-friendly responsive design.

⸻

Contributors
	•	Prathamesh Bhavsar – Backend Development, AI Integration, UI Design

⸻

License

This project is licensed under the MIT License.

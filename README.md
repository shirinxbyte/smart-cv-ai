# 🧠 Smart CV Text Generator with AI

This is a simple AI-powered tool that helps you create a professional "About Me" section for your CV.

## Features

- Generates CV text based on role, skills, and interests
- Uses OpenAI API and Streamlit for UI

## Installation

```bash
git clone https://github.com/your-username/smart-cv-ai.git
cd smart-cv-ai
pip install -r requirements.txt
streamlit run app.py


## 🔐 OpenAI API Key
To use this app, you need a free OpenAI API key.
Get it here: https://platform.openai.com/account/api-keys

Paste your key into the app when prompted.

🧠 Prompt Engineering Example
The tool uses a structured prompt like this:

nginx
Copy
Edit
Write a short, professional 'About Me' section for a CV based on:
- Role: {user input}
- Skills: {user input}
- Interests: {user input} 


📂 File Structure
bash
Copy
Edit
smart-cv-ai/
│
├── app.py            # Streamlit UI
├── prompts.py        # Prompt generation logic
├── requirements.txt  # Dependencies
└── README.md         # This file


💼 Use Cases
Job seekers who want to polish their resumes

Students learning prompt engineering and AI APIs

Portfolio projects to demonstrate practical AI use


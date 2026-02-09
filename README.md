🤖 AI Student Assistant
📌 Overview

AI Student Assistant is a lightweight web-based AI chatbot designed to help students get clear and concise study answers instantly.

The system is built using:

Python Flask for backend

Google Gemini Generative AI API for intelligent responses

HTML/CSS/JS frontend for chat interaction

This project demonstrates real-world integration of Generative AI into an educational web application.

✨ Features

Study-focused AI question answering

Clean chat interface

Fast API-based response generation

JSON-based communication between frontend and backend

Error handling for empty input or API issues

🧠 How It Works

User enters a question in the web interface.

Flask backend receives the message via POST /chat.

The message is sent to Google Gemini model with a study-assistant prompt.

Gemini generates a clear educational response.

Response is returned as JSON and displayed in the chat UI.

🛠️ Tech Stack

Python

Flask

Google Generative AI (Gemini API)

HTML / CSS / JavaScript

▶️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/ai-student-assistant.git
cd ai-student-assistant

2️⃣ Install dependencies
pip install flask google-generativeai

3️⃣ Add your Gemini API key (IMPORTANT)

Create an environment variable instead of hard-coding:

export GEMINI_API_KEY="your_api_key_here"


Then update code:

genai.configure(api_key=os.getenv("GEMINI_API_KEY"))

4️⃣ Run the app
python app.py


Open in browser:

http://127.0.0.1:5000

📂 Project Structure
ai-student-assistant/
│── app.py
│── templates/
│    └── index.html
│── static/
│── README.md

🎯 Learning Outcomes

Integrating Generative AI with Flask

Designing AI-powered educational tools

Understanding API handling & prompt engineering

Building real-time chatbot web apps

👨‍💻 Author

Zafarullah Khan
AI Student – NUTECH Islamabad

⭐ Support

If you like this project, consider starring the repository and sharing feedback.


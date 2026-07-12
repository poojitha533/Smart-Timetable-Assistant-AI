Smart Timetable Assistant AI Agent 📅🤖

An AI-powered calendar management application that helps students organize their academic schedules, track assignments, manage exam dates, detect scheduling conflicts, and receive intelligent reminders.

🚀 Features
📅 Google Calendar Integration
📝 Create, Edit, and Delete Events
📚 Class Schedule Management
⏰ Assignment Deadline Tracking
🔔 Reminder and Notification System
🤖 Natural Language Scheduling Assistant
⚠️ Conflict Detection and Resolution
📊 Schedule Dashboard
☁️ Cloud Deployment using Streamlit
🛠️ Tech Stack
Frontend
Streamlit
Backend
Python
LangChain
APIs
Google Calendar API
Gmail API (Optional)
Database
SQLite
Libraries
streamlit
google-api-python-client
google-auth-oauthlib
langchain
pandas
schedule
python-dotenv
📂 Project Structure
smart-timetable-assistant/
│
├── app.py
├── calendar_manager.py
├── scheduler.py
├── reminder.py
├── database.py
├── requirements.txt
├── .env
├── README.md
├── assets/
├── templates/
└── screenshots/
⚙️ Installation
Step 1: Clone Repository
git clone https://github.com/your-username/smart-timetable-assistant.git
cd smart-timetable-assistant
Step 2: Create Virtual Environment
python -m venv venv

Activate:

Windows:

venv\Scripts\activate

Linux/Mac:

source venv/bin/activate
Step 3: Install Dependencies
pip install -r requirements.txt
Step 4: Configure Environment Variables

Create a .env file:

GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
OPENAI_API_KEY=your_api_key
Step 5: Run Application
streamlit run app.py
📸 Screenshots

Add screenshots of:

Dashboard
Calendar View
Assignment Tracker
Reminder System
🧠 Working Flow
User logs into the application.
Connects Google Calendar.
Adds classes, assignments, and exams.
AI analyzes schedule conflicts.
Suggests free time slots.
Sends reminders and notifications.
📊 Future Enhancements
Multi-calendar synchronization
Mobile application
WhatsApp reminders
Smart study planner
Predictive scheduling using AI
Voice assistant integration
👨‍💻 Team Members
Member 1 – Project Lead: poojithagopishetty
Member 2 – hasini.j
Member 3 – g.karthik

🌤️ Mood Tracker API (Flask)

A simple backend API built with Flask that allows users to log moods, retrieve logs, and generate insights and summaries.
This project is designed as a lightweight backend service for a mood tracking app.

🚀 Features

Add mood logs

Fetch all logs

Get mood summaries

Generate insights

REST API endpoints

CORS enabled for frontend integration

📂 Project Structure
mood/
│── app.py
│── requirements.txt
│── README.md
⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
2️⃣ Create Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate
3️⃣ Install Dependencies
pip install -r requirements.txt

If no requirements file exists:

pip install flask flask-cors
▶️ Run Server
python app.py

Server runs at:

http://127.0.0.1:5000
📡 API Endpoints
Base URL
http://127.0.0.1:5000
GET /api/logs

Returns all mood logs.

POST /api/logs

Add a mood entry.

Body (JSON)

{
  "mood": "happy",
  "note": "Had a great day!"
}
GET /api/summary

Returns summary statistics.

GET /api/insights

Returns insights generated from mood data.

🛠 Tech Stack

Python

Flask

Flask-CORS

⚠️ Development Server Warning

Flask’s built-in server is for development only.
For production use a WSGI server like:

Gunicorn

uWSGI

Waitress (Windows)

📌 Future Improvements

Database integration

Authentication

Frontend dashboard

Charts & analytics

User accounts

👨‍💻 Author

Prashant Gupta

📜 License

This project is open-source and free to use.

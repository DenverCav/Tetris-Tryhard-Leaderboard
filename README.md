A full-stack web application for tracking, submitting, and comparing competitive Tetris scores within the Tetris.com community.

Built with Flask and a SQLite database, featuring Discord OAuth authentication, personal score tracking, and a global leaderboard system.

⸻
Features

Discord OAuth2 login system

Guest/demo mode for quick access

Global leaderboard with game filtering

Personal profile pages with score history

Score submission (personal + official entries)

Moderator tools for score validation and deletion

CSRF protection and session security

Basic analytics and progression tracking

⸻
Tech Stack

Python (Flask)

SQLite

Flask-Dance (OAuth)

HTML / CSS / Jinja2 templates

Pytest (testing framework)

⸻
Installation
1. Clone the repository
git clone https://github.com/your-username/repo-name.git

cd repo-name

2. Install dependencies 
pip install flask flask-dance python-dotenv pytest coverage
Environment Variables (.env setup)
This project uses a .env file to securely store sensitive configuration values.

Create a file called .env inside the project root.

The required variables inside of the .env file are:

FLASK_SECRET_KEY=your_flask_secret_key
DISCORD_CLIENT_ID=your_discord_client_id
DISCORD_CLIENT_SECRET=your_discord_client_secret

 

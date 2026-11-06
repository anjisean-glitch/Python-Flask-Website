# Python Flask Website

A Python Flask web application that combines assignment management with an AI-powered chat assistant.

## Features

### Assignment Management
- Create new assignments.
- View saved assignments.
- Edit assignment details.
- Update assignment status.
- Delete assignments.
- Store assignment records using SQLite.

### AI Chat Assistant
- Integrated Google Gemini API.
- Accepts user questions through a web interface.
- Generates AI responses.
- Handles API errors.

### Additional Features
- Flask routing.
- HTML templates with Jinja.
- CSS styling.
- SQLite database integration.

## Technologies Used
- Python
- Flask
- SQLite
- HTML
- CSS
- Google Gemini API
- Git and GitHub

## Project Structure
- `app.py` – Main Flask application and routes.
- `database.py` – SQLite database connection and initialization.
- `templates/` – HTML templates.
- `static/` – CSS styling.
- `assignment.txt` – Assignment CRUD practice instructions.

## Setup and Installation

1. Clone this repository.
2. Install the required packages by running: `pip install Flask python-dotenv google-genai`
3. Create a `.env` file in the project root and add: `GEMINI_API_KEY=your_api_key`
4. Run the application using: `python app.py`
5. Open the local address displayed in your terminal.

## Database
The application uses SQLite to store assignment records. The database and assignments table are initialized automatically when the application starts.

## About
This project demonstrates my practical development with Python, Flask, databases, web development and API integration.

# FitBuddy – AI Fitness Plan Generator

## Requirements
- Python installed
- VS Code (recommended)
- A Google Gemini API key

## Setup Instructions

1. Download and extract the FitBuddy project.
2. Open the project folder in VS Code.
3. Open the terminal inside the folder containing `app/main.py` and `requirements.txt`.
4. Create a virtual environment:

   `py -m venv venv`

5. Activate it on Windows:

   `.\venv\Scripts\Activate.ps1`

6. Install the dependencies:

   `py -m pip install -r requirements.txt`

7. Create a `.env` file in the project root and add your own API key:

   `GEMINI_API_KEY=your_own_api_key`

8. Start the application:

   `py -m uvicorn app.main:app --reload`

9. Open the website in a browser:

   `http://127.0.0.1:8000`

## Features
- AI-generated 7-day workout plans
- Goal-based fitness recommendations
- Nutrition and recovery tips
- Feedback-based workout plan updates
- User and workout-plan storage
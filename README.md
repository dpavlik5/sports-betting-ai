# AI Sports Betting Predictor

An intelligent application that uses AI/ML models to track sporting statistics in real-time and predict the likelihood of bets winning.

## Features

✅ **Real-time Data Ingestion** - Fetches live sports stats from multiple APIs  
✅ **AI Prediction Engine** - ML models calculate bet win probability  
✅ **User Dashboard** - Track stats, enter bets, view likelihood percentages  
✅ **Real-time Updates** - Probabilities update as games progress  
✅ **Historical Analysis** - Learn from past games and betting odds  
✅ **Notification System** - Alerts when probabilities shift significantly  

## Tech Stack

- **Frontend:** React + TypeScript + Tailwind CSS
- **Backend:** Python + FastAPI
- **ML/AI:** scikit-learn, TensorFlow, XGBoost
- **Database:** PostgreSQL
- **Sports Data APIs:** The Odds API, API-Football
- **Deployment:** Docker + AWS/Heroku

## Getting Started

### Prerequisites
- Python 3.9+
- Node.js 16+
- PostgreSQL 12+
- Docker & Docker Compose

### Quick Start

1. **Clone the repository**
	```bash
	git clone https://github.com/dpavlik5/sports-betting-ai.git
	cd sports-betting-ai
	```

2. **Create and activate a Python virtual environment**
	```bash
	python3 -m venv .venv
	source .venv/bin/activate
	pip install -r requirements.txt
	```

3. **Install frontend dependencies**
	```bash
	cd frontend
	npm install
	cd ..
	```

4. **Configure environment**
	- Copy `.env.example` to `.env` and update DB/API keys as needed.

5. **Run with Docker Compose (recommended)**
	```bash
	docker compose up --build
	```

6. **Run services locally (without Docker)**
	- Start PostgreSQL and create the database.
	- Run the backend:
	  ```bash
	  uvicorn backend.main:app --reload
	  ```
	- Start the frontend:
	  ```bash
	  cd frontend
	  npm start
	  ```

Refer to the sections below for advanced configuration and deployment.

## Project Structure

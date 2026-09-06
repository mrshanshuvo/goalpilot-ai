# GoalPilot AI

AI-powered goal planning and progress tracking application that turns user goals into structured plans, daily tasks, and AI-generated progress feedback.

## Features

* AI-powered goal analysis
* Automated daily task generation
* Task completion tracking
* AI-powered progress evaluation
* Personalized feedback and next steps
* REST API
* Swagger/OpenAPI documentation
* OpenAI SDK with OpenRouter
* Express.js backend

## How It Works

```text
User Goal
   ↓
AI Goal Analysis
   ↓
Daily Task Generation
   ↓
Task Tracking
   ↓
AI Progress Evaluation
```

## Tech Stack

* Node.js
* Express.js
* JavaScript
* OpenAI SDK
* OpenRouter
* REST API
* Swagger / OpenAPI
* dotenv

## API Endpoints

| Method | Endpoint                      | Description                       |
| ------ | ----------------------------- | --------------------------------- |
| GET    | `/api/goals`                  | Get all goals                     |
| GET    | `/api/goals/:goalId`          | Get goal details                  |
| POST   | `/api/analyze-goal`           | Analyze a goal and generate tasks |
| PATCH  | `/api/tasks/:taskId`          | Update task status                |
| POST   | `/api/goals/:goalId/evaluate` | Evaluate goal progress            |

## Getting Started

```bash
git clone https://github.com/mrshanshuvo/goalpilot-ai.git
cd goalpilot-ai
npm install
```

Create a `.env` file:

```env
OPENROUTER_API_KEY=your_api_key
PORT=5000
```

Run the project:

```bash
npm run dev
```

API:

```text
http://localhost:5000
```

Swagger:

```text
http://localhost:5000/swagger
```

## Project Structure

```text
goalpilot-ai/
├── data/
├── public/
├── ai-agents.js
├── server.js
├── storage.js
├── package.json
└── README.md
```

## Project Status

Completed AI-powered goal planning and progress tracking application.

## License

MIT License

## Author

**Shahid Hasan Shuvo**

Full Stack Developer

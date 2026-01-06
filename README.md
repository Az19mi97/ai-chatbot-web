# AI Chatbot Web App

A modern, visually appealing AI chatbot built with **React** for frontend and **Node.js/Express** for backend, integrated with **OpenAI API** for AI responses. This project demonstrates full-stack development, including frontend UI/UX, backend API, and AI integration.
<img width="723" height="550" alt="ai-chatbot" src="https://github.com/user-attachments/assets/d0e2f620-44ed-4042-9ee2-08dd4bf568dc" />

---

## Features

- **Real-time chat interface** with modern UI/UX design
  - Gradient backgrounds, shadows, and rounded chat bubbles
  - Smooth fade-in animations for messages
  - Typing indicator with pulsing dots for AI
- **AI-powered responses** using OpenAI's GPT models
- **Timestamps** on all messages
- **Responsive layout** for desktop and mobile
- **Enter key support** and loading state on send button
- **Environment variable support** for secure OpenAI API key

---

## Tech Stack

| Layer         | Technology                                     |
|---------------|-----------------------------------------------|
| Frontend      | React, Tailwind CSS                           |
| Backend       | Node.js, Express, dotenv                       |
| AI            | OpenAI GPT API (e.g., GPT-4o-mini)            |
| HTTP Client   | Fetch API                                     |
| Dev Tools     | VS Code, npm/yarn                             |

---

## Setup & Usage

### 1. Clone the repository
```bash
git clone https://github.com/your-username/ai-chatbot-web.git
cd ai-chatbot-web
```

### 2. Backend setup
```bash
cd backend
npm install
```

#### Create a .env file with your OpenAI API key:
```bash
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxx
```
Start the backend server:
```bash
node server.js
```
The server will run at http://localhost:5050.

### 3. Frontend setup
```bash
cd ../frontend
npm install
npm start
```

### 4. Usage
	1.	Open your browser at http://localhost:3000
	2.	Type a message in the input field and press Enter or click Send
	3.	The AI will respond with a generated reply
	4.	Watch typing indicator and timestamps for a modern chat experience

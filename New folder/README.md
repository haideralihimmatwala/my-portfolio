# Chatbot Project

Google Gemini API se chalne wala AI chatbot.

## Setup

### 1. Gemini API key hasil karein
https://aistudio.google.com/apikey par jaakar free API key banayein (Google account chahiye).

### 2. API key .env file mein dalein
`.env` file kholein aur `GEMINI_API_KEY` ki value apni asli key se replace karein.

### 3. Project dependencies install karein
```bash
npm install
```

### 4. Server chalayein
```bash
npm start
```

### 5. Browser mein open karein
```
http://localhost:5000
```

## Folder Structure
```
chatbot-project/
├── public/
│   └── index.html      # Frontend chat UI
├── server.js            # Express backend
├── package.json
├── .env                  # Config (port, model name)
├── .gitignore
└── README.md
```

## Notes
- API key kabhi bhi public repo (GitHub) mein commit mat karein — `.gitignore` already `.env` ko ignore karta hai.
- Model badalna ho to `.env` file mein `GEMINI_MODEL` change karein (e.g. `gemini-2.0-flash`, `gemini-2.5-flash`).
- Gemini free tier mein rate limits hain — zyada traffic ke liye paid plan chahiye hoga.

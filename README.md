# 🤖 Gemini MCP Commander
## Autonomous PR Commander
### Google Cloud × GitLab Hackathon 2024

## 🎯 What It Does
Automatically resolves GitLab issues using AI:
- Receives webhook when issue is created
- AI triages and classifies the issue
- Reads repository code automatically
- Generates code fix using LLaMA3-70b
- Creates branch + commits patch
- Opens Merge Request with full explanation
- Posts comment on original issue

## 🛠️ Tech Stack
- **Frontend**: HTML5, Tailwind CSS, Vanilla JS
- **Backend**: FastAPI (Python 3.11)
- **AI**: Groq LLaMA3-70b + LLaMA3-8b
- **Integration**: GitLab REST API (MCP Pattern)

## 🚀 How to Run

### 1. Clone the repo
git clone <your-repo-url>
cd Gemini-MCP-agent

### 2. Setup Backend
cd Backend
pip install -r requirements.txt
cp .env.example .env
# Add your API keys to .env

### 3. Start Server
python main.py

### 4. Open Frontend
Open Frontend/index.html in browser

## 📋 Environment Variables
GROQ_API_KEY=your-groq-key
GITLAB_TOKEN=your-gitlab-token
GITLAB_PROJECT_ID=your-project-id
GITLAB_BASE_URL=https://gitlab.com
PORT=8000

## 🎬 Demo
[Link to demo video:https://drive.google.com/drive/folders/1JRrMk06S2h3vrVPnldAGBijO8bQpmVrg]

## 📸 Screenshots
[Add screenshots here:https://drive.google.com/drive/folders/1JRrMk06S2h3vrVPnldAGBijO8bQpmVrg]

# Neural Odds 🧠⚡

> AI-Powered Sports Betting Analytics Platform with Liquid Glass Design

Neural Odds is a completely free, self-hosted sports betting analysis platform that combines advanced AI analytics with a professional, minimalist Apple-like interface.

## ✨ Features

- **🎨 Liquid Glass UI**: Professional Apple-inspired design with glassmorphism effects
- **🤖 Local AI Analytics**: Powered by Ollama (Llama 3.1) for sophisticated analysis
- **📊 Real-time Data**: Automated collection from multiple free sources
- **🎯 Smart Predictions**: Statistical models and AI-powered insights
- **📱 Responsive Design**: Beautiful on desktop, tablet, and mobile
- **💾 Self-Hosted**: Complete ownership of your data and analysis

## 🚀 Quick Start

```bash
# 1. Clone and setup
git clone <your-repo-url> neural-odds
cd neural-odds
npm install

# 2. Copy environment file
cp .env.example .env.local
# Edit .env.local with your API keys

# 3. Setup database
npm run db-setup

# 4. Install Ollama (for AI)
curl -fsSL https://ollama.ai/install.sh | sh
ollama pull llama3.1:8b

# 5. Start development server
npm run dev

🛠 Tech Stack

Frontend: Next.js 14, TypeScript, Tailwind CSS, Framer Motion
AI: Ollama (Local LLM), Custom algorithms
Database: SQLite3 (local), Better-sqlite3
Data Sources: ESPN API, Web scraping, Reddit API
Design: Liquid glass components, Apple-inspired aesthetics
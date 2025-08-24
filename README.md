# 🌰 HazelnutPilot AI  
*Built by Vaidehi Kulkarni for Mosaic Buildathon 2025*  

---

## 📌 Overview  
Hazelnut AI is a **no-code, AI-powered QA automation tool**.  
Upload a PRD → AI generates runnable tests → one-click run with Playwright → auto **Issues.xlsx**, screenshots, and dashboard.  

---

## ✨ Features  
- 📝 **PRD → Test Cases (AI)**  
- ▶️ **Run Web + API tests** (Playwright + Axios)  
- 📊 **Dashboard:** pass/fail donuts, run history, issues chart  
- 📂 **Artifacts:** screenshots, video recordings, Issues.xlsx  
- 🔗 **Viewer link:** share read-only test results  

---

## 🛠️ Tech Stack  
- **Frontend:** React (Vite), Tailwind, Framer Motion  
- **Backend:** Node.js, Express  
- **Testing Engine:** Playwright (browser), Axios (API)  
- **AI:** Ollama (local Llama3) / OpenRouter (cloud) / Template fallback  
- **Hosting (demo-ready):** Vercel (UI) + Render (API)  

---

## 🚀 Getting Started  

### Prerequisites  
- Node.js 20+  
- [Ollama](https://ollama.com) (for local AI) OR OpenRouter API key  
- Playwright browsers:  
  ```bash
  npx playwright install --with-deps

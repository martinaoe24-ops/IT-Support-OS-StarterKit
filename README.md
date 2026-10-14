# 🛠️ IT-Support-OS | Helpdesk & AI Ticket System

> **Production-Ready Starter Kit for Developers & SysAdmins**  
> Fast, lightweight, and 100% self-hosted Helpdesk system powered by **FastAPI, SQLite, Vanilla JS**, and a **3-tier Hybrid AI Engine**.

---

### 🚀 Get Full Source Code & Developer License
[![Buy Developer License](https://img.shields.io/badge/BUY_LICENSE-$49_USD-0284C7?style=for-the-badge&logo=paypal&logoColor=white)](https://payhip.com/b/vHJPG)
[![Instant Download](https://img.shields.io/badge/DOWNLOAD-.ZIP_+_PDF_GUIDE-10B981?style=for-the-badge)](https://payhip.com/b/vHJPG)

> 💡 **Includes:** Complete Python source code, pre-configured `install.bat` / `start.bat` scripts, SQLite canonical DB, automated test suite, and a complete Architecture & Setup PDF Guide.

---

## 📸 Overview & Key Features

**IT-Support-OS** is built to save you weeks of boilerplate development. Deploy a private, local, or cloud-hosted Helpdesk without monthly SaaS fees per user or vendor lock-in.

- **🤖 Hybrid AI Ticket Analyzer (3-Tier Fallback):**
  1. **Google Gemini API** (`gemini-1.5-flash`) for low-cost, high-speed LLM ticket classification.
  2. **OpenAI API** (`gpt-4o-mini`) native integration with structured JSON responses.
  3. **Local Heuristic Engine:** 100% offline, free, and private fallback logic that works without internet or API keys.
- **⚡ Automated One-Click Deployment (Windows):**
  - `install.bat`: Automatic `venv` setup, dependency installation (`requirements.txt`), and database seeding.
  - `start.bat`: One-click execution that boots FastAPI/Uvicorn and launches your browser at `http://127.0.0.1:8000`.
- **📊 Complete Operational Modules:**
  - Real-time Metrics Dashboard & Ticket Management.
  - User Directory with bulk CSV importer and UTF-8 / accent support.
  - Built-in Knowledge Base (KB) & Guided Troubleshooting module.
  - Atomic Database Backup/Restore system and UTF-8 BOM CSV exports.

---

## 🛠️ Tech Stack & Architecture

| Component | Technology |
| :--- | :--- |
| **Backend Framework** | Python 3.10+ / FastAPI / Uvicorn |
| **Database** | SQLite3 (Lightweight, atomic backup/restore) |
| **Frontend** | Vanilla HTML5 / CSS3 / JavaScript (No Node.js, npm, or heavy build step required) |
| **AI Integration** | Google Gemini SDK / OpenAI SDK / Offline Heuristic Rule Engine |
| **Testing** | Pytest (100% passing unit & automated end-to-end integration tests) |

---

## ⚡ Quick Start (Local Windows Setup)

```bash
# 1. Clone or download the repository / package
# 2. Run automated installer script (creates venv & sets database)
install.bat

# 3. Start application (launches server and opens browser automatically)
start.bat

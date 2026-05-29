<!-- Header -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=260&color=0:0f0f0f,50:0d1117,100:161b22&text=Muhammad%20Ali%20Kasana&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20%26%20AI%20Engineer&descAlignY=58&animation=fadeIn"/>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-malikasana.github.io-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://malikasana.github.io)
[![CV](https://img.shields.io/badge/CV-Professional-161b22?style=for-the-badge&logo=readthedocs&logoColor=white)](https://malikasana.github.io/cv)
[![Email](https://img.shields.io/badge/Gmail-malikasana2810-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:malikasana2810@gmail.com)
[![PyPI](https://img.shields.io/badge/dynamic/json?url=https://pypi.org/pypi/smartgate-ai/json&query=$.info.version&label=smartgate-ai&style=for-the-badge&logo=pypi&logoColor=white&color=3775A9&prefix=v)](https://pypi.org/user/malikasana)
[![PyPI](https://img.shields.io/badge/dynamic/json?url=https://pypi.org/pypi/gemini-flux/json&query=$.info.version&label=gemini-flux&style=for-the-badge&logo=pypi&logoColor=white&color=3775A9&prefix=v)](https://pypi.org/project/gemini-flux)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-Spaces-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/malikasana)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=malikasana&style=for-the-badge&color=0d1117&label=PROFILE+VIEWS)

</div>

---

*I build complete systems — mobile frontends, AI pipelines, security infrastructure, and developer tools.*

---

## 🛠 Stack

**Mobile**
<img src="https://skillicons.dev/icons?i=flutter,dart,androidstudio" />

**Backend**
<img src="https://skillicons.dev/icons?i=python,fastapi,nodejs,flask,redis" />

**AI / ML**
<img src="https://skillicons.dev/icons?i=pytorch" />
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_Whisper-F55036?style=flat-square&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-111827?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)

**Database & Auth**
<img src="https://skillicons.dev/icons?i=postgres,supabase,mongodb" />

**Infra & DevOps**
<img src="https://skillicons.dev/icons?i=docker,github,linux" />
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

**Security**
![XChaCha20](https://img.shields.io/badge/XChaCha20--Poly1305-1e293b?style=flat-square)
![Curve25519](https://img.shields.io/badge/Curve25519-0f172a?style=flat-square)
![Double Ratchet](https://img.shields.io/badge/Double_Ratchet_PFS-111827?style=flat-square)
![RSA](https://img.shields.io/badge/RSA--2048-1e293b?style=flat-square)

---

## 🚀 Projects

### 🤖 AI & Developer Tools

| Project | Description |
|---------|-------------|
| [**ai-gateway**](https://github.com/malikasana/ai-gateway) | Local AI bridge server — talk to Claude, ChatGPT, DeepSeek and Gemini without API keys. OS-level automation, Flask HTTP queue, browser UI, ngrok-ready. |
| [**gemini-flux**](https://github.com/malikasana/gemini-flux) `pip install gemini-flux` | Smart Gemini API key manager. Token-aware sliding window scheduling across N keys × N GCP projects. ~10,800 free requests/day with 8 keys. Auto-rotation, model fallback chain, daily resets. |
| [**smartgate-ai**](https://github.com/malikasana/smartgate-ai) `pip install smartgate-ai` | AI-powered semantic firewall for databases. 6-layer pipeline (IP → queue → size → hash → AI → save). Authenticates *data* instead of users. Supports Gemini, DeepSeek, OpenAI with auto-fallback. |
| [**preflight**](https://github.com/malikasana/preflight) `npx @malikasana/preflight-mcp` | MCP server that gives Claude Code accurate knowledge of your machine — environment detection, live package versions from npm/PyPI/pub.dev, auto-generates CLAUDE.md. Token-efficient, self-healing. |

### 🔐 Security & Privacy

| Project | Description |
|---------|-------------|
| [**securechat-client**](https://github.com/malikasana/securechat-client) | Zero-knowledge E2EE Android messenger. Curve25519 key exchange, XChaCha20-Poly1305 encryption, Double Ratchet PFS (new key every message), unanimous member approval. No phone number. No third party. Self-hosted. |
| [**securechat-server**](https://github.com/malikasana/securechat-server) | Pure relay server for securechat. Never reads or stores message content — only routes encrypted blobs. RSA signature verification on every request. Deployable on Render, Railway, or Raspberry Pi. |

### 📱 Mobile Apps

| Project | Description |
|---------|-------------|
| [**pakconstitution-ai**](https://github.com/malikasana/pakconstitution-ai) | Pakistan's 1973 Constitution + all 27 amendments as a RAG chatbot. Ask plain-English questions, get answers with exact article citations. Flutter + FastAPI + ChromaDB + sentence-transformers + Gemini. |
| [**videodub**](https://github.com/malikasana/videodub) *(WIP)* | Automatic video dubbing — upload in any language, get it back dubbed. Full Flutter client + FastAPI backend + AI pipeline architecture complete. AI components in progress. |
| [**voxar**](https://github.com/malikasana/voxar) | Voice recorder with dual transcription: Groq Whisper API + a custom Whisper encoder-decoder built from scratch in PyTorch (trained on LJSpeech, val loss 0.2262, zero pretrained weights). |
| [**flower-classifier-frontend**](https://github.com/malikasana/flower-classifier-frontend) | Flutter app identifying 102 flower species via ResNet-34. Pretrained model: 98.53% accuracy. Scratch model: 89.49%. Top-5 predictions + flower info panel. HuggingFace Spaces backend. |

### 📊 Machine Learning & Data

| Project | Description |
|---------|-------------|
| [**equityiq**](https://github.com/malikasana/equityiq) | Two end-to-end ML projects on financial data. (1) Classifies 10,765 companies by market cap tier — Random Forest + K-Means, F1: 0.79. (2) Forecasts growth with XGBoost on 30 years of scraped data — predicted 9/10 AI boom companies for 2023 using only pre-2020 training. [Live demo on HuggingFace](https://huggingface.co/spaces/malikasana/equityiq). |

### 🌐 Web

| Project | Description |
|---------|-------------|
| [**multi-grid**](https://github.com/malikasana/multi-grid) | Interactive long multiplication worksheet. Breaks any number up to 9999 × 99 into place-value steps visually. Vanilla HTML/CSS/JS. [Live site](https://multigrid-d104.onrender.com). |
| [**malikasana.github.io**](https://github.com/malikasana.github.io) | Personal portfolio and CV — [programmer theme](https://malikasana.github.io) · [professional theme](https://malikasana.github.io/cv). |

---

## 📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=malikasana&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github"/>

<img height="180em" src="https://streak-stats.demolab.com?user=malikasana&theme=github-dark-blue&hide_border=true"/>

<br/><br/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=malikasana&layout=compact&theme=github_dark&hide_border=true&langs_count=8&cache_seconds=1800"/>

</div>

---

## 📍 Status

🟢 &nbsp;Open to opportunities &nbsp;·&nbsp; 📍 Pakistan &nbsp;·&nbsp;

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:161b22,50:0d1117,100:0f0f0f&section=footer"/>

<sub>github.com/malikasana · malikasana.github.io · malikasana2810@gmail.com</sub>

</div>

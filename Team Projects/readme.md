<div align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
  <h1>🤝 Collaborative Ventures</h1>
  <p><i>High-impact projects built in the heat of hackathons and research sprints.</i></p>
  
  <p align="center">
    <img src="https://skillicons.dev/icons?i=python,tensorflow,fastapi,react,nodejs,nextjs,typescript,tailwind,docker,git,github" />
  </p>
  
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
</div>

---

## 🏆 Featured Collaborations

*Showcasing teamwork, rapid prototyping, and real-world impact.*

---

### 🌾 Cropix
**AI-Powered Precision Agriculture Platform**

Cropix is an end-to-end agricultural intelligence platform that leverages **5 specialized machine learning models** to deliver data-driven insights for farmers. The system combines deep learning and classical ML to address critical agricultural challenges—from crop selection to disease diagnosis.

**🧠 ML Architecture:**
- **Disease Detection (CNN)** — TensorFlow/Keras-based computer vision model analyzing crop imagery to identify diseases with high accuracy
- **Market Forecasting (LSTM)** — Time-series neural network predicting agricultural commodity prices to optimize selling timing
- **Crop Recommendation (KNN/Random Forest)** — Multi-factor ML engine considering soil composition (N-P-K), pH, humidity, and rainfall
- **Fertilizer Optimization (XGBoost)** — Gradient boosting model prescribing precise nutrient formulations
- **Weather Prediction** — Historical data analysis for rainfall and seasonal forecasting

**⚙️ Tech Stack:**
- **Frontend:** Next.js 15 (App Router), React, TypeScript, Tailwind CSS, Framer Motion, Radix UI, Recharts
- **Backend:** FastAPI, Uvicorn ASGI server, Pydantic validation
- **ML/AI:** TensorFlow, Keras, scikit-learn, XGBoost, NumPy, Pandas, Joblib serialization
- **Deployment:** Containerized microservices architecture

**🔗 Links:** [Live Demo](https://cropixbitlyfe.vercel.app/) | [GitHub](https://github.com/ShaikhWarsi/Cropix)

---

### 🍯 Agentic Honeypot
**Autonomous AI Counter-Intelligence System**

A **Top 15 National Finalist** at the HCL-Guvi Hackathon, this backend-centric cybersecurity platform deploys AI agents that convincingly simulate vulnerable victims to engage scammers in extended conversations. The system autonomously extracts critical intelligence while wasting attacker resources.

**🎯 Core Capabilities:**
- **Deceptive Persona Engine** — LLM-powered agent adopting convincing victim personas to lure scammers
- **Intelligence Extraction** — Automated harvesting of scammer operational details, payment methods, and infrastructure
- **Persistent Engagement** — Multi-turn conversation management to maximize time-wasting and data collection
- **Evidence Compilation** — Structured report generation for law enforcement with complete interaction logs

**⚙️ Tech Stack:**
- **Backend:** Python, AsyncIO, FastAPI
- **AI/LLM:** Groq SDK (Llama 3.3-70B), LangGraph for state orchestration
- **Data Layer:** PostgreSQL for conversation persistence, structured schema extraction
- **Deployment:** Hugging Face Spaces with Docker containerization

**🏆 Recognition:** Top 15 National Finalist — HCL-Guvi Hackathon

**🔗 Links:** [Hugging Face Space](https://huggingface.co/spaces/Rachit-Tw/Agentic-Space/tree/main)

---

### 🎣 Fish Pish
**Multi-Layer Phishing Detection Ecosystem**

A comprehensive cybersecurity solution combining a **real-time web dashboard** with a **Chrome browser extension** for ubiquitous link protection. The system employs a multi-stage weighted scoring engine that transitions from rapid heuristic checks to deep AI forensic analysis.

**🛡️ Defense Architecture:**
- **Chrome Extension (MV3)** — Shadow DOM-injected hover protection providing instant risk triage (🔴 Danger / 🟡 Suspicious / 🟢 Safe)
- **Multi-Stage Analysis Engine:**
  - Tier 1: Google Safe Browsing API + SSL certificate forensics
  - Tier 2: Groq LLM (Llama 3.3-70B) contextual URL anatomy analysis
  - Weighted scoring formula aggregating technical and AI signals
- **In-Memory Caching** — Sub-100ms response for previously analyzed URLs
- **Educational Modules** — Interactive learning hub with phishing awareness training

**⚙️ Tech Stack:**
- **Frontend:** Next.js 15, Tailwind CSS, Framer Motion, Lucide React
- **Backend:** Node.js, Express, TypeScript
- **AI/Security:** Groq SDK, Google Safe Browsing API, Custom SSL forensic engine
- **Extension:** Vite, TypeScript, Manifest V3, Shadow DOM injection

**🔗 Links:** [GitHub](https://github.com/Rachit-Tiwari-7/Fish-Pish)

---

### 🎨 RangManch
**"Legacy-as-a-Service" Marketplace for Rural Artisans**

**Best UI/UX Award Winner** — A next-generation decentralized marketplace platform engineered to bridge the gap between Indian rural artisans and global consumers. Unlike conventional e-commerce, RangManch preserves cultural context while eliminating exploitative middlemen.

**🎯 Problem-Solution Fit:**
- **Eliminates Middlemen** — Direct artisan-to-consumer model preserving up to 70% margins lost to traditional platforms
- **Zero Technical Barrier** — GST-free onboarding, no complex inventory management
- **Cultural Context Preservation** — Rich storytelling alongside products, showcasing artisan heritage and craft lineage
- **Direct Negotiation** — Built-in communication channels for custom orders and bulk pricing

**⚙️ Tech Stack:**
- **Frontend:** Next.js 15, React, TypeScript, Tailwind CSS
- **Animation:** Framer Motion for cinematic, immersive user experience
- **UI Components:** Radix UI primitives with custom design system
- **Cloud Infrastructure:** Vercel Edge Network for high-performance global delivery

**🏆 Recognition:** Best UI/UX Award — Hackathon Winner

**🔗 Links:** [Live Demo](https://rangmanchindia.vercel.app/)

---

### 🎯 AscendPrep (InterviewLab)
**Next-Gen AI Technical Interview Platform**

**1st Prize Hackathon Winner** — An immersive interview preparation platform featuring a **live voice-enabled AI interviewer** that analyzes not just answers, but posture, confidence, communication patterns, and problem-solving approach. The system provides holistic interview readiness assessment.

**🎙️ Core Features:**
- **Live Voice AI Interviews** — WebRTC-powered low-latency (<2s) voice interaction with GPT-4o-mini
- **Multimodal Analysis** — Computer vision assessment of posture, eye contact, and confidence metrics
- **Resume-Aware Interrogation** — Dynamic question generation based on user's specific background and claimed expertise
- **DSA Practice Arena** — Company-tagged problems with Monaco Code Editor integration
- **ATS Resume Engine** — Resume builder with real-time ATS scoring and optimization suggestions
- **Docker Sandboxing** — Secure code execution environment for technical assessments

**⚙️ Tech Stack:**
- **Frontend:** Next.js 15 (App Router), TypeScript, Tailwind CSS, Zustand state management, TanStack Query, Monaco Editor
- **Backend:** FastAPI, AsyncIO, Pydantic, Instructor (structured LLM outputs)
- **Voice/Video:** LiveKit SFU Server, WebRTC, OpenAI Whisper (STT), ElevenLabs TTS
- **AI Orchestration:** LangGraph state machines, GPT-4o-mini
- **Infrastructure:** Docker sandboxing, Redis caching, PostgreSQL persistence

**🏆 Recognition:** 1st Prize — Hackathon Winner

**🔗 Links:** [Live Demo](https://ascendPrep.vercel.app) | [GitHub](https://github.com/ShaikhWarsi/AscendPrep)

---

<div align="center">
  <br />
  <a href="../README.md">🏠 Back to Hub</a>
  <br />
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
</div>

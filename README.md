# 👋 Hi, I’m Reginald Cobb  

Founder of **Cobb Innovation Hangar(https://cobbinnovationhangar.com/)** — where aviation‑grade systems thinking meets Software and AI experimentation, compute and hardware systems exploration, and having fun!

I’m a versatile engineer with a broad background that spans **full-stack web and mobile development**, **backend systems architecture**, **computer‑vision pipelines**, and **embedded hardware systems**. My work bridges the gap between robust software engineering and empirical machine learning research. I value clarity, craftsmanship, and momentum, and I am driven by a desire to understand how things work beneath the surface to turn complexity into something simple, elegant, and useful.

---

## 🧩 Technical Focus Areas  

My technical expertise spans across several domains, emphasizing both robust engineering and experimental research. In **Full-Stack & Cross-Platform Development**, I build responsive web applications and mobile apps using modern frameworks. My **Backend & Systems Engineering** work involves building robust APIs, data pipelines, and automation tools using Python and cloud services.

In **AI and Machine Learning**, I focus on experiment design, evaluation pipelines, and reproducible workflows. I have  experience with **Computer Vision and Edge AI**, utilizing tools like OpenCV, Jetson Nano, ONNX, TensorRT, and OpenVINO and want to learn more!   

---

## 🚀 AI-Powered Projects

I actively leverage **AI joint programming and AI development "partners"** to accelerate development, build complex utilities, and explore agentic workflows. By integrating AI into my development process, I have been able to rapidly prototype and deploy functional applications across various domains.

| Project Name | Description | Key Technologies |
|---|---|---|
| **[JSON Fixer](https://github.com/reginaldcobb/json-fixer)** | A single-page utility that detects and repairs malformed JSON from LLM outputs. It validates structure, pretty-prints, and explains errors in plain English. Designed for developers and AI power users. | TypeScript, AI |
| **[The Vibe Codex](https://github.com/reginaldcobb/thevibecodex)** | An AI Coding Cheat Sheet for vibe coders. It serves as a comprehensive resource and guide for developers working alongside AI coding assistants. | TypeScript,  AI |
| **[I Wish I Could Ask](https://github.com/reginaldcobb/iwishicouldask-)** | A full-stack web application built to facilitate structured Q&A, allowing users to ask questions to people and organizations. | TypeScript,  AI |

Beyond these highlighted repositories, I have utilized various AI tools to develop several other tools, including **HomeRadar** (a real estate tracking utility), **Nutriplan** (a nutritional planning application), **Fantasy Football Toolkit & ETL** (data pipelines for fantasy sports), **AlphaTracker** (a financial tracking app), and **TagMirror** (an iOS application to scan and compare product tags).

---

## 🔬 Research & Substantive Technical Projects

The following projects represent the deepest technical work across my portfolio — spanning algorithmic engineering, observability systems, hybrid AI architectures, SaaS product engineering, mobile AI pipelines, and ML research. Each has been selected for the sophistication of its implementation, not just its surface-level functionality.

| Project | Domain | Technical Depth | Key Technologies |
|---|---|---|---|
| **[json-fixer](https://github.com/reginaldcobb/json-fixer)** | Algorithmic Engineering | Hand-written, zero-dependency, three-phase JSON repair engine. Phase 0 handles Unicode normalization (BOM, curly quotes, full-width CJK punctuation, zero-width characters) using a context-aware string scanner. Phase 1 performs structural repair (missing commas and colons) with line-number tracking. Phase 2 runs a hand-rolled JSON Schema (draft-07 subset) validator. Every fix is typed and categorized. Full Vitest suite organized into P0/P1/P2/roundtrip tiers. | TypeScript, Vite, Vitest, Express, Radix UI |
| **[HomeRadar](https://github.com/reginaldcobb/HomeRadar)** | Observability & Systems | Multi-module Python observability platform for home-network monitoring. Implements anomaly detection that classifies outages as `FAIL_LOCAL` vs `FAIL_ISP` by correlating independent probes (gateway, Cloudflare, Google, HTTP endpoints). Computes p95 latency statistics, detects outage windows, and generates daily summaries. Includes a FastAPI dashboard, Grafana integration, and a PostgreSQL schema. | Python, FastAPI, PostgreSQL, Grafana |
| **[vitaminpicker](https://github.com/reginaldcobb/vitaminpicker)** | Hybrid AI / Firebase Functions | Monorepo with a hybrid rules-engine-first + Gemini AI recommendation pipeline. The deterministic rules engine scores supplement candidates by priority from quiz inputs (goals, diet, symptoms, lifestyle), handles deduplication (e.g., magnesium glycinate vs. threonate), and constrains the Gemini search space before calling the AI for structured rationale generation (`mechanism`, `evidenceLevel`, `timeToEffect`, `safetyNotes`). Includes an affiliate monetization layer and a full design system. | TypeScript, React Native, Expo, Firebase, Gemini API |
| **[Rankify](https://github.com/reginaldcobb/rankify)** | SaaS Product Engineering | Full-stack Next.js SaaS with an Elo rating engine (K=32) for pairwise item ranking. The Premium "Smart Pairing" feature sorts items by Elo proximity and deprioritizes pairs with >200 Elo gap, reducing redundant comparisons by 50–100+ for large lists. Includes Genkit AI content moderation on all user-generated text, Stripe subscription webhooks (Pro/Premium tiers), Firebase Admin SDK custom claims, Playwright E2E tests, and Google AdSense for free-tier monetization. | Next.js, TypeScript, Firebase, Genkit, Stripe, Playwright |
| **[Pricelyt (tagmirror-ios-xcode-main)](https://github.com/reginaldcobb/tagmirror-ios-xcode-main)** | Mobile AI Pipeline | Production React Native (Expo) app that sends base64-encoded shelf price tag images to Gemini 2.5 Flash with a structured JSON schema prompt. Extracts product name, total price, original and standardized units (oz/lbs/ml/L normalization for cross-unit comparison), and currency symbol with strict validation. Implements multi-key rotation with exponential backoff across 4 Gemini API keys. Geolocation-tags each scan with reverse-geocoded store name and address. RevenueCat subscriptions, Apple Sign-In, Expo EAS build pipeline. | TypeScript, React Native, Expo, Gemini API, Firebase, RevenueCat |
| **[fantasy_football](https://github.com/reginaldcobb/fantasy_football)** | ML Pipeline | XGBoost + Optuna hyperparameter optimization pipeline for fantasy football player performance prediction. Multi-source feature engineering combines player statistics, weather data, and coaching tendencies. Includes a data processor, model trainer, and prediction evaluator with reproducible experiment tracking. | Python, XGBoost, Optuna, Pandas, Jupyter |
| **[Balanced-Fork](https://github.com/reginaldcobb/Balanced-Fork)** | Full-Stack AI App | Next.js nutrition and hydration tracker using Google Genkit with Gemini 2.5 Pro for meal photo analysis. The typed Genkit flow extracts food items, estimated calories, macro breakdown (protein/carbs/fat in grams), and allergen cross-references personalized to user dietary preferences. Hydration tracker applies drink-type-specific hydration factors (e.g., coffee = 0.8×, fitness drinks = 0.95×) to compute net hydrated volume. Firebase Firestore persistence, Recharts data visualization, Radix UI components. | Next.js, TypeScript, Genkit, Gemini API, Firebase, Recharts |

---

## 🚧 Representative Projects (from my GitHub)

My broader portfolio reflects a deep interest in full-stack development, systems engineering, computer vision, and empirical evaluation. 

| Project | Focus Area | Description |
|---|---|---|
| **MySitterHub** | Web Application | A full-stack web application designed to connect users, built with TypeScript and deployed on Vercel. |
| **People‑Counter‑On‑Edge** | Computer Vision | An empirical CV pipeline using Intel OpenVINO. It performs real‑time inference on constrained hardware and includes robustness testing across various lighting and motion conditions. This project demonstrates an empirical evaluation mindset relevant to safety research. |
| **Token Network** | Systems Engineering | A Python and Arcade-based project featuring deterministic logic. It includes a custom grid renderer, UI system, state machines, rule evaluation, and puzzle generation. The aviation‑inspired architecture emphasizes clarity and control, demonstrating the ability to build complex systems from scratch. |
| **ml‑tutorial** | Machine Learning | A collection of ML experimentation notebooks covering both fundamentals and applied machine learning. It showcases my ability to structure experiments and communicate results clearly. |
| **Text‑Match / speech** | Model Behavior | A browser‑based speech recognition and keyword detection tool. It demonstrates an interest in model behavior, triggers, and evaluation, useful for thinking about model organisms and behavioral analysis. |
| **Maker + Embedded Projects** | Hardware | Various projects utilizing Arduino, IoT sensors, Fritzing circuits, and Jetson Nano CV nodes. These projects highlight my comfort with real‑world failure modes, sensor noise, and adversarial environments. |

---

## 🔧 Core Tech Stack

My technology stack is diverse, allowing me to build end-to-end systems from embedded devices to web applications.

| Category | Technologies |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, HTML/CSS, Dart, C++, Bicep, Swift |
| **Frontend Frameworks** | React Native, Ionic 6, Flutter, HTML/CSS, TypeScript |
| **Backend & Cloud** | FastAPI, Django, PostgreSQL, Azure App Service, Vercel |
| **ML/AI** | OpenCV, ONNX, TensorRT, OpenVINO, embeddings, Manus, Claude, Gemini, Copilot AI, Jupyter Notebooks |
| **Embedded & Hardware** | Jetson Nano, Arduino, IoT devices, Fritzing |
| **Tooling & Architecture** | GitHub Actions, Linux systems, experiment tracking, Markdown documentation |


---

## 🤝 Collaboration Interests

I am always open to collaborating on projects that push the boundaries of what's possible. I am particularly interested in partnering on machine learning, front- and back-end system development, and software/hardware integration efforts.    

---

## 🔗 Connect with Me

- **LinkedIn:** https://www.linkedin.com/in/reginaldcobb/  
- **Cobb Innovation Hangar:** https://cobbinnovationhangar.com/  
- **GitHub:** https://github.com/reginaldcobb  

---

## ⚠️ Repo Refresh Underway
I’m restructuring older repos, improving documentation, and aligning everything with a more research‑oriented workflow to support upcoming AI safety work.


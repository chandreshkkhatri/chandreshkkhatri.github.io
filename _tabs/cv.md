---
layout: page
icon: fas fa-file-alt
order: 3
title: CV
---

# Chandresh Kumar
**Senior Software Engineer**
Gurugram, India | +91-8114423917 | chandreshkkhatri@gmail.com
[LinkedIn](https://linkedin.com/in/chandreshkkhatri) | [GitHub](https://github.com/chandreshkkhatri)

---

## WORK EXPERIENCE

### Freelance Work and personal projects | *Bengaluru, India* | *July 2025 – Present*
**Alpha Terminal — AI-Powered Quantitative Trading Platform** `|` *Python · Nautilus Trader · Gemini API · MCP-based Orchestration*
* Engineered an agentic AI framework to automate the end-to-end quantitative trading lifecycle, spanning from automated strategy generation to system deployment.
* Integrated the Gemini API with custom MCP-based orchestration to manage real-time backtesting and execution via Nautilus Trader.

**Lucidity Chat — AI-Powered Conversational Platform** `|` *Next.js · TypeScript · MongoDB · Google Gemini*
* Architected a full-stack AI chat application using Next.js 15 App Router and React 19, integrating Google Gemini 2.5 via Vercel AI SDK with real-time server-sent event streaming.
* Built a Slack-style threaded conversation system and an interactive Canvas view (React Flow/Dagre), supporting nested replies, persistent visual mapping, and a custom text annotation system to spawn focused sub-threads.
* Implemented token-based usage metering with per-model cost calculation, monthly quota enforcement, and Razorpay integration with HMAC webhook verification for automated Pro subscriptions.
* Engineered secure backend services including NextAuth.js v5 authentication, MongoDB connection pooling, JWT sessions, and SWR for optimistic client-side data synchronization.

**SpikeyCoins — Trading Platform** `|` *Full-Stack TypeScript · Next.js 16 · Node.js/Express · MongoDB · Binance & Upstox APIs · PWA*
* Designed and built a Progressive Web App (PWA) multi-broker trading platform for crypto futures (Binance) and Indian equities (Upstox), featuring a responsive terminal with TradingView charts, live orderbook, and push notifications.
* Engineered a robust Node.js backend integrating Binance Spot/Futures REST APIs behind a dynamic Bottleneck rate-limiter, preventing IP bans by syncing with real-time `x-mbx-used-weight-1m` headers under concurrent load.
* Implemented a persistent WebSocket price service fanning out orderbook data via SSE, and a polling Binance Order Monitor that automatically triggers stop-loss/take-profit algo orders via the Binance Algo API.
* Developed a journal sync engine that reconstructs full round-trip trades from raw fill history—computing weighted average prices and realized PnL—surfaced through an auto-synced Analyst’s Journal and a Trading Gym sandbox.

**Open Mandi — Crypto Derivatives Exchange** `|` *Full Stack Engineer `|` Next.js 16 · TypeScript · PostgreSQL*
* Built a complete Web3-adjacent commodities exchange from scratch, engineering a custom trading and matching engine supporting perpetual futures, 50x leverage, and automated liquidations.
* Developed autonomous algorithmic market-making and hedging bots integrating directly with the Binance Futures API.
* Handled end-to-end user flows including Firebase Auth sessions, wallet deposits/withdrawals, and complex real-time terminal UI components.

**Reweave — AI-Powered Video Generation Toolkit** `|` *Python · FFmpeg · Google Gemini API · MoviePy · Fal.ai/Replicate APIs*
* Designed and developed a Python-based intelligent multimodal pipeline using the Gemini API to automatically perform chunked native transcription and summarization of 2+ hour YouTube videos, bypassing unstable scraping libraries.
* Engineered dynamic video assembly using MoviePy and complex FFmpeg filters, rendering 5 distinct video modes including Ken Burns slideshows, AI-lipsynced avatars (via Fal.ai/Replicate), and reactive audiograms.
* Implemented custom subtitle synchronization logic using character-count heuristics to calculate precise millisecond weights, eliminating text-to-speech (TTS) timing drift in burned-in SRT captions.

**Chess Rebundled — Chess Learning & Multiplayer Platform** `|` *Full-Stack Software Engineer*
* Engineered a scalable, real-time multiplayer application for learning chess notation and playing live matches using Next.js, React, Node.js, Fastify, and Socket.io with Redis caching for low-latency state synchronization.
* Integrated Stockfish.js (WebAssembly) for performant client-side board evaluations, while implementing robust data persistence through MongoDB for historical games and Firebase for secure user authentication.

### Software Development Engineer III
**Radiolab Technology (ByajKhata)** | *Jaipur, India* | *June 2024 – June 2025*

* Led backend architecture and feature development for a dynamic financial services app (Node.js backend, Flutter frontend)
* Delivered analytics APIs, calculation engines, and a referral system, enhancing functionality and boosting user engagement by 30%
* Enhanced system reliability and scalability through code refactoring, load testing, and advanced security (e.g., multi-device login prevention, MongoDB auth)
* Optimized AWS infrastructure (EC2, API Gateway, Load Balancer, Redis caching), reducing response times by 40% and maintaining 99.9% uptime
* Integrated third-party services and payment systems (Gupshup, AWS S3, Cashfree) with secure checkout flows and webhook automation
* Enabled 12L+ GMV across 2,500+ transactions in 3 months with a 97% payment success rate and robust API documentation via SwaggerUI

### Co-Founder, Principal Software Engineer (Generative AI)
**AOEPL** | *Gurgaon, India* | *July 2022 – March 2024*

* Built ActuAl Evaluation Desk, an AI-powered UPSC mock test evaluator using GPT-4 and Azure OCR, reducing costs by 70% while improving grading accuracy
* Implemented RAG pipelines with vector databases and GPT-4 code interpreter to improve factual accuracy and numerical reasoning
* Designed and evaluated LLM-based multi-agent architectures using SuperAGI, MetaGPT, and Superagents.sh for autonomous content generation
* Led a 3-member cross-functional squad in an agile Scrum setup, delivering 10+ MVP iterations with consistent sprint success

### Software Development Engineer III
**Pluang Technologies** | *Gurugram, India* | *Jan 2022 – July 2022*

* Owned the development of IPO services for a new app launch in Indonesian stocks, enabling the execution of the platform's first IPO (GoTo)
* Instituted a shared test automation framework, cutting regression cycle time from 3 days to 9 hours and lowering escaped bugs by 50%
* Mentored junior developers through code reviews and design discussions to foster best practices in scalable Node.js development

### Freelance Developer
**Self Employed** | *Jan 2019 – Jan 2022*

* Delivered end-to-end full-stack services for the edtech platform Actively Learn, providing scalable and reliable backend architecture
* Developed a full-stack trading and analytics platform with live trading features using Express.js and MongoDB
* Integrated Kite Connect API for real-time data, order management, and portfolio tracking with advanced charting features
* Set up CI/CD pipelines using Jenkins and Travis CI, reducing release cycle times by 70% and minimizing errors through Dockerization

### Analyst | Full Stack Developer
**Citicorp Services India Private Limited** | *July 2016 – Jan 2019*

* Architected an Angular 2 migration framework adopted by 15 teams, trimming legacy JSP migration effort by 70% and saving ~3.4 Cr annually
* Co-developed a self-service API gateway portal (React, SwaggerUI) enabling 500+ developers to configure routes autonomously
* Cut API onboarding SLA from 5 days to 6 hours

---

## EDUCATION

* **Indian Institute of Technology, Bombay** | *2011 – 2016*
    * Bachelor of Technology - Electrical Engineering
    * Masters of Technology - Microelectronics

---

## SKILLS, TOOLS AND FRAMEWORKS

* **Languages & Frameworks:** Node.js (TypeScript), Python (FastAPI, pandas), React / React Native, Postgres, MongoDB, Redis, RabbitMQ, Docker, Jenkins
* **Cloud & AI:** AWS (EC2, S3, Lambda, API Gateway), Azure ML Studio, Vector DBs, LlamaIndex, RAG, OpenAI APIs, MCP servers, Agentic AI, multi-agent frameworks
* **Practices & Tools:** Clean Architecture, TDD/BDD, CI/CD (GitHub Actions, Jenkins), Agile (Scrum), JIRA
* **Certifications:** Google Project Management Certificate (2023), Udacity Data Analyst Nanodegree (2020)

---

## EXTRA-CURRICULARS AND ACHIEVEMENTS

* **JEE AIR 170**
* **Chess:** First Position, King's Rated Chess – 2014, IIT Bombay
* **Mountaineering:** Basic Mountaineering Course, ABVIMAS, Manali, Himachal Pradesh

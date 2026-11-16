<p align="center">
  <a href="https://aryansr.com">
    <img src="./assets/banner.svg" alt="Aryan Singh Rajpoot — AI/ML Engineer and Full Stack Developer" width="100%" />
  </a>
</p>

<p align="center">
  <a href="https://aryansr.com"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-aryansr.com-5b9dff?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://leetcode.com/u/aryanrajpoot1006"><img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-300%2B%20solved-f89f1b?style=for-the-badge&logo=leetcode&logoColor=white" /></a>
  <a href="mailto:rsingharyan10@gmail.com"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-Email%20me-ea4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img alt="Open to work" src="https://img.shields.io/badge/Open%20to%20work-Full%20Stack%20Developer-22c55e?style=for-the-badge" />
</p>

<p align="center">
  🎓 Pre-final-year CSE (AI) at <b>Bennett University</b> &nbsp;|&nbsp; 🧠 Backend · Retrieval · Full Stack
</p>

<p align="center">
  🌐 <b>Live demos, project write-ups and resume → <a href="https://aryansr.com">aryansr.com</a></b>
</p>

---

I'm a Computer Science (AI specialization) student who builds things from start to finish: backend APIs, database-driven systems and the web interfaces on top of them. Recent work includes a hybrid retrieval API with a 117-test evaluation harness, and an LLM inference server checked by a 27-test correctness suite with Prometheus monitoring. I'm looking for a **Full Stack Developer** role where I can own features end to end.

## 🧩 Quick Facts

```yaml
role:          AI/ML Engineer / Full Stack Developer
now:           Full Stack Developer Intern @ Valoron Consulting
studying:      B.Tech CSE (AI), Bennett University · 2023 – 2027
based_in:      Ghaziabad, India
research:      IEEE (CICTN 2025) and ACM (ICCA 2026) co-author · 1st place, DRDO WRITE IT
shipped:       Hybrid retrieval API (117 tests) · LLM inference server (27 tests) · double-entry wallet (77 tests)
competitive:   LeetCode 300+ solved · top 3.1% · 92.7% acceptance
portfolio:     https://aryansr.com
```

## 💼 Experience

**Full Stack Developer Intern — Valoron Consulting** · New Delhi · Aug 2026 – Present

- Built the Flutter client for **Fanito**, a creator-economy app with a feed, shorts, tasks, wallet, DMs and AI features. 185 of 185 Flutter tests pass, across 260+ commits.
- Added database locking and idempotency to money flows. Tests show 200 concurrent ₹50 tips on a ₹100 balance give exactly 2 successes, and 10 identical payment webhooks give exactly 1 credit.
- Rewrote row-level security policies, added 26 database indexes, repaired the CI/CD pipeline and fixed 12 failing tests.
- Worked on the AI features: a RAG navigation agent, task matching and an AI Twin with voice, with fallbacks for retired or rate-limited LLM providers.

**AI/ML Intern — Labmentix** · May – Aug 2026

- Built a SimpleRNN vs. LSTM pipeline that forecasts Tesla stock prices at 1, 5 and 10-day horizons, with technical-indicator features and Keras Tuner search.
- Trained Logistic Regression, Random Forest and Gradient Boosting models to predict high vs. low salary Data Science roles from 956 Glassdoor listings, validated with hypothesis testing and F1 / AUC-ROC.

## 🚀 Featured Work

Full write-ups, diagrams and recordings are on **[aryansr.com](https://aryansr.com)**.

### 💳 [Valoron Wallet](https://github.com/aryan2006-singh/valoron-wallet-core-mvp) &nbsp;·&nbsp; [Live](https://valoron-wallet-core-mvp.vercel.app)
`Next.js` `TypeScript` `PostgreSQL` `Stripe` `WebSockets`

A USD wallet on an append-only double-entry ledger, so every balance can be rebuilt from its own history. Transfers, Stripe card deposits and withdrawals, escrow and two-factor sign-in. **77 automated tests**, no stored balance columns, idempotent money movements.

### 🔎 [GST-RAG](https://github.com/aryan2006-singh/gst-rag) &nbsp;·&nbsp; [Live](https://gst-rag.vercel.app)
`Python` `FastAPI` `React` `BM25` `Statistical testing`

Hybrid BM25 + dense retrieval with cross-encoder reranking over Indian tax law, plus a supersession graph so a question can be answered as of a date. **117-test evaluation harness** (Recall@k, MRR, nDCG, bootstrap confidence intervals). The public demo runs BM25 only.

### 🤖 [PayPilot](https://github.com/aryan2006-singh/paypilot) &nbsp;·&nbsp; [Live](https://paypilot-peach.vercel.app)
`Python` `FastAPI` `React` `TypeScript` `Razorpay` `MCP`

Multi-agent payments operations assistant: five specialist agents answer why a payment failed, where a refund is and whether a settlement matches. Tools are also exposed over MCP. **49 pytest tests** and a router eval set.

### ⚡ [slotserve](https://github.com/aryan2006-singh/slotserve) &nbsp;·&nbsp; [Live](https://slotserve.vercel.app)
`Python` `PyTorch` `FastAPI` `Prometheus`

LLM inference server with token-level continuous batching over a custom slot-addressed KV cache. OpenAI-compatible API, SSE streaming and Prometheus metrics. **2.73× throughput vs. static batching** on a heavy-tailed workload, **27 tests** against HuggingFace `generate()`.

### 🌐 Websites
- **[Solene Heights](https://real-estate-website-cfa2.vercel.app)** — a real estate site for a 17-floor tower: turn it in 3D, pick a floor, step into every room in 360° (listings and prices are illustrative).
- **[DeepHook](https://deephook.vercel.app)** — a concept and waitlist site for on-chain order-book hooks, with an interactive demo.

## 📄 Research & Publications

- 🥇 **1st place, DRDO WRITE IT Competition** — "Automated Semantic Lung Segmentation in Chest CXR Images Using Deep Learning Models"
- 📘 **IEEE · CICTN 2025** — co-author, "A MultiResUNet-based Deep Learning Architecture for Accurate Lung Segmentation in Chest X-Rays"
- 📗 **ACM · ICCA 2026** — co-author, "Grammatical Error Correction in Low-Resource Language: A Case Study of Hindi Using Data Augmentation and Multi-Model Evaluation"

## 🛠 Tech Stack

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=py,js,dart,cpp&theme=dark" alt="Python, JavaScript, Dart, C++" />

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=react,flutter,redux,html,css&theme=dark" alt="React, Flutter, Redux, HTML, CSS" />

**Backend & APIs**<br/>
<img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs&theme=dark" alt="FastAPI, Flask, Node.js" /><br/>
REST API design · SSE streaming

**Databases**<br/>
<img src="https://skillicons.dev/icons?i=postgres,supabase,sqlite&theme=dark" alt="PostgreSQL, Supabase, SQLite" /><br/>
pgvector

**AI / ML**<br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,pandas,numpy&theme=dark" alt="PyTorch, TensorFlow, Pandas, NumPy" /><br/>
LangGraph · Sentence Transformers · NLP

**Testing & tools**<br/>
<img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,prometheus&theme=dark" alt="Git, GitHub, GitHub Actions, Docker, Prometheus" /><br/>
Regression test harnesses · k6 load testing

## 📜 Certifications

- HackerRank — Problem Solving (Basic), Frontend Developer (React), REST API (Intermediate)
- Coursera — Build Basic GANs (DeepLearning.AI)
- Coursera — Foundations of Neural Networks Specialization (Johns Hopkins University)

## 🧭 Currently

- 🔨 Shipping features end to end as a Full Stack Developer Intern at Valoron Consulting
- 🌱 Going deeper on retrieval evaluation, LLM serving and agent workflows
- 🎯 Looking for a Full Stack Developer role, where I can own features from database to interface

## 📊 GitHub Stats

<p align="center">
  <img alt="Aryan's GitHub contribution streak" src="https://streak-stats.demolab.com/?user=aryan2006-singh&background=0e1b34&border=1c2d52&stroke=1c2d52&ring=5b9dff&fire=5b9dff&currStreakNum=eaf1ff&sideNums=eaf1ff&currStreakLabel=5b9dff&sideLabels=b4c4e4&dates=8497bb" />
</p>

## 🔗 Connect

<p align="center">
  <a href="https://aryansr.com"><b>Portfolio · aryansr.com</b></a> &nbsp;·&nbsp;
  <a href="https://leetcode.com/u/aryanrajpoot1006">LeetCode</a> &nbsp;·&nbsp;
  <a href="mailto:rsingharyan10@gmail.com">Email</a>
</p>

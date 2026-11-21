### Hi, I'm Cuong

I'm a student developer looking for a **Software Engineering internship**. Most of my work is full-stack web development with **C#/.NET** and **React/TypeScript**. I'm also building on a TypeScript Chrome extension and have done one NLP project in Python.

### Projects

**[VocabLearning](https://github.com/SCuong/PBL3_vocab_web)**: a full-stack English vocabulary app, built as a team project of three. I wrote most of the backend and frontend.
- Built with ASP.NET Core (.NET 10), EF Core, PostgreSQL, React 19 and Tailwind, with Docker Compose for local runs.
- The review scheduler is based on SM-2 spaced repetition. It is a pure, unit-tested class kept separate from the database code.
- Authentication: PBKDF2 password hashing, anti-forgery tokens, rate limiting and Google sign-in.
- Includes an admin side for vocabulary, topics, exercises, users and learning analytics.

**[Themis](https://github.com/SCuong/Themis)**: a Chrome extension (Manifest V3) where Claude, ChatGPT, Gemini, Grok and DeepSeek take on roles and review each other's answers. It is modified from [OpenTeam](https://github.com/afumu/openteam). My changes:
- Rebuilt it from TypeScript source instead of shipped bundles.
- Added a persistent attachment cleanup queue and per-tab frame rules.
- Fixed workflow correctness bugs.
- Redesigned the UI.
- Set up tests that run in CI.

**[Bert](https://github.com/SCuong/Bert)**: an AI course project that fine-tunes `bert-base-uncased` to classify the sentiment of English hotel reviews.
- On the held-out test set it scored 84.8% accuracy, against 81.9% for a TF-IDF + Logistic Regression baseline.
- It is also far slower at inference than the baseline. The report covers that trade-off and the error analysis.
- Includes a FastAPI demo.

### Tools

- **Used in projects:** C#, ASP.NET Core, EF Core, PostgreSQL, React, TypeScript, Tailwind CSS, Docker, xUnit, Playwright, GitHub Actions
- **Some experience:** Python, PyTorch / Hugging Face Transformers, FastAPI, Chrome Extensions (MV3), Java

### Contact

vumanhcuongppt@gmail.com

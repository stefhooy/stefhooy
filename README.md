<div align="center">

<!-- Looping header banner -->
<img src="https://raw.githubusercontent.com/stefhooy/stefhooy/main/assets/banner/header_nabla_true.webp" width="900" alt="Header banner" />

</div>

### Data Analyst at Gameloft (Monetization), building toward Applied AI and Data Science

Background spans analytics engineering, agentic AI systems, and applied ML across professional and personal projects. MSc in Business Analytics & Data Science (IE University) and BBA in Business Analytics & Data Science (HEC Montréal).

**Currently working with:**
- Analytics & monetization: Python, SQL, BigQuery, Looker, LookML
- Agentic AI systems: LangGraph, RAG, FastAPI, LLMs
- Applied ML: model evaluation, testing, CI/CD, Docker
- Data science: forecasting, recommender systems, statistical modeling

---

## Featured Projects

**Ludo: Agentic AI Game-Market Analyst**  
Natural-language-to-SQL agent that answers video game market questions over a Steam catalog by writing and executing real SQL against a database. Uses LangGraph agent routing, embedding-based schema retrieval (RAG) instead of prompt-stuffing, and a read-only connection guarded by an independent SQL parser. Evaluated with a hand-labeled recall benchmark (1.000 recall at production top-k) and per-request cost tracking; ships an MCP server exposing the same tools to Claude Desktop/Cursor.  
`Python · FastAPI · LangGraph · DuckDB · Next.js · Docker`  
[GitHub](https://github.com/stefhooy/full_stack_project) · [Live](https://full-stack-project-sepia-nine.vercel.app/)

**Reverie: GRU and NCF Watch-Next Engine**  
Movie recommender combining a sequential GRU (predicts and re-ranks the next watch in real time) with a Neural Collaborative Filtering model trained on ~9.9M Letterboxd ratings. Evaluated with leave-one-out testing and confidence intervals: the NCF model beats a movie-mean baseline for 94% of users (RMSE 1.37 vs. 1.62), and the GRU model outperforms item-kNN and popularity baselines. Ships as a full product: FastAPI backend with JWT auth, React/Vite/TypeScript frontend, accounts, watchlists, and a "Blend" feature that merges two users' picks.  
`Python · PyTorch · FastAPI · React · TypeScript`  
[GitHub](https://github.com/em-ech/reverie)

**Smart Residential Price Estimation: Production-Oriented MLOps Pipeline**  
End-to-end pipeline predicting Ames, Iowa house prices (LassoCV, R² 0.80-0.89) built as a modular, tested system rather than a notebook: experiment tracking and model registry via Weights & Biases, a FastAPI service with `/health` and `/predict` endpoints, Docker containerization, and GitHub Actions CI/CD that tests and builds on PR and auto-deploys to Render on release. 54 tests, 84% coverage.  
`Python · scikit-learn · FastAPI · Docker · GitHub Actions · Weights & Biases`  
[GitHub](https://github.com/jclujan/my-project1-mlops) · [Live](https://my-project1-mlops.onrender.com/docs) *(Render free tier: first request may take a few seconds to wake up)*

**The Blockbuster Formula: Bayesian Box Office Predictor**  
Bayesian Network model predicting box office outcomes (Flop to Blockbuster) on 3,278 films (2000-2025) from TMDb. Full pipeline: API collection, feature engineering (actor prestige scoring, budget tiers, release windows), structure learning via the PC algorithm, and a baseline ML comparison.  
`Python · pgmpy · XGBoost · Streamlit`  
[GitHub](https://github.com/stefhooy/box-office-bayesian) · [Live](https://blockbuster-bayesian.streamlit.app/) *(Streamlit Community Cloud: click through the wake-up screen if the app is asleep)*

**IE Sustainability Datathon: 1st Place** *(team project)*  
Won a time-bound datathon analyzing aviation traffic and CO₂ emissions across European airspace using EUROCONTROL data (2010-2025), identifying trends between flight activity and environmental impact.  
`Python · Tableau`  
[GitHub](https://github.com/stefhooy/datathon-2025)

---

## Master's Research Capstone

**[Mixed-Frequency Forecasting of Energy CPI: MIDAS Models, LASSO Regularisation, and State-Space Extensions](https://github.com/stefhooy/midas_capstone)**

Research capstone benchmarking MIDAS regression variants against ARIMAX, XGBoost, and LSTM for forecasting US consumer energy inflation from weekly crude oil prices. Introduces three novel model extensions (CLM-SS, LASSO-MIDAS, Kernel U-MIDAS) and a three-layer expanding-window validation design. The best MIDAS variant reduces forecast error by roughly 31% versus ARIMAX, with significance confirmed via Diebold-Mariano testing.  
`R · midasr · LASSO · State-space models`

---

## Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**ML / AI**  
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)
![pgmpy](https://img.shields.io/badge/pgmpy-00A896?style=for-the-badge&logoColor=white)

**Data Engineering**  
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Apache NiFi](https://img.shields.io/badge/Apache%20NiFi-728E9B?style=for-the-badge&logo=apache&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white)

**MLOps**  
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

**Web Dev**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Visualization / BI**  
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Looker](https://img.shields.io/badge/Looker-4285F4?style=for-the-badge&logo=looker&logoColor=white)
![LookML](https://img.shields.io/badge/LookML-4285F4?style=for-the-badge&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge&logo=googleanalytics&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

**Other**  
![Pygame](https://img.shields.io/badge/Pygame-000000?style=for-the-badge&logo=python&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-009688?style=for-the-badge&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Oracle VirtualBox](https://img.shields.io/badge/Oracle%20VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)
![DBeaver](https://img.shields.io/badge/DBeaver-382923?style=for-the-badge&logo=dbeaver&logoColor=white)
![SQL Server Management Studio](https://img.shields.io/badge/SSMS-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

---

## Professional Experience

**Data Analyst, Monetization**  
Gameloft Sofia Studio · Aug 2026 - Present  
Analyzes 300+ GB of gameplay and monetization data (SQL, BigQuery) to evaluate campaigns, pricing changes, player behaviour, and the in-game economy; validates telemetry against spec and evaluates the reliability of a BigQuery-based AI agent's output.

**Data Engineering & Analytics Intern, Pricing & Risk**  
MPower Ventures · Apr 2026 - Jul 2026  
Built Python/SQL data pipelines and reusable simulation and optimization workflows integrating FX, inflation, and pricing data to evaluate pricing and risk strategies across FX depreciation scenarios of up to 20%.

**Data Analyst**  
Streamwise · Jan 2025 - May 2026  
Evaluated ML model outputs in Python across a 300-user beta, analyzing detection performance, latency, and failure patterns to support model and product improvements.

**Business Analyst I Intern, Operations & Planning**  
Intact Financial Corporation · May 2025 - Aug 2025  
Built a ServiceNow-Jira operational dashboard and automated 300+ Excel reports, cutting reporting time by roughly 30%. 1st place, Intact National Intern Case Competition (200+ participants).

---

## Education

<a href="https://www.ie.edu/university/studies/academic-programs/master-business-analytics-data-science/" target="_blank">
  <img src="https://raw.githubusercontent.com/stefhooy/stefhooy/main/assets/logos/ie_university%20(1).png" height="44" alt="IE University" title="IE University" />
</a>

**MSc in Business Analytics & Data Science**  
IE University School of Science & Technology, Madrid · Sept 2025 - Jul 2026  
Advanced Tech Track (Top 15%) · IE Collaboration Scholarship · Advanced AI Concentration

<a href="https://www.hec.ca/en/" target="_blank">
  <img src="https://raw.githubusercontent.com/stefhooy/stefhooy/main/assets/logos/hec_montreal%20(1).png" height="44" alt="HEC Montréal" title="HEC Montréal" />
</a>

**BBA, Business Analytics & Data Science**  
HEC Montréal · Aug 2022 - May 2025  
Bilingual program (French & English)

<a href="https://www.uni-corvinus.hu/en/" target="_blank">
  <img src="https://raw.githubusercontent.com/stefhooy/stefhooy/main/assets/logos/corvinus.png" height="44" alt="Corvinus University Budapest" title="Corvinus University Budapest" />
</a>

**Exchange Semester, Business Administration**  
Corvinus University of Budapest · Feb 2024 - Jun 2024

---

## Other Projects

### Agentic AI & LLM Apps

**Hermes: AI European Travel Planner**  
AI travel agent that builds personalized multi-city European itineraries. Scores 80 European cities using a proximity-aware system (activity match, budget fit, seasonality, and geographic routing from the departure city), estimates transport across flights, trains, and buses, pulls live Wikipedia descriptions and Open-Meteo weather data, and generates a 12-month pricing calendar. Runs fully locally via Ollama (llama3.1:8b) with no paid API keys required. 90 automated tests covering agent logic, data processing, and API integrations.  
`Python · LangChain · LangGraph · Ollama · Streamlit`  
[GitHub](https://github.com/stefhooy/euro_ai_agent)

**VC Startup Pitch Evaluator** *(team project)*  
Multi-agent GenAI system that analyses startup pitch decks end-to-end using the Gemini API and LangGraph, including a ReAct fact-checking agent that validates founder claims against live web sources. Outputs a structured investment memo with dimension scores (market, team, product, traction) and flags low-confidence decisions for human analyst review.  
`Python · LangGraph · Gemini API`  
[GitHub](https://github.com/MarianGarabana/GenAI_GroupProject) · [Live](https://vc-analyst.streamlit.app/)

### Analytics Tools

**Personal Finance Analytics Package**  
Python package that categorizes bank CSV transactions using a regex rule engine and produces monthly budget summaries. Immutable dataclasses, CLI via argparse, pytest-tested, packaged with uv and published to TestPyPI. Backend library for a companion Streamlit app.  
`Python · argparse · pytest · uv`  
[GitHub](https://github.com/stefhooy/pocketwise-finance) · [TestPyPI](https://test.pypi.org/project/pocketwise-finance/)

**Budget Calculator: Exchange Edition**  
Live Streamlit app for tracking spending across countries and currencies. Started as a personal tool during a winter 2024 exchange in Budapest, rebuilt with multilingual support (EN/FR/ES), geographic spend maps, file import/export, and multi-currency conversion.  
`Python · Streamlit`  
[GitHub](https://github.com/stefhooy/Budget-Calculator-Exchange) · [Live](https://budget-calculator-tracker.streamlit.app/)

### In Progress

**Marvin: Reinforced AI Chess Bot**  
AlphaZero-style chess engine in PyTorch: a dual-head ResNet policy/value network trained via MCTS self-play RL, with optional supervised pretraining on grandmaster PGN games and a Flask web UI to play against it with live Elo tracking. Includes a pytest suite.  
`Python · PyTorch · Flask`  
[GitHub](https://github.com/stefhooy/chess-rl-bot)

### Just for Fun

**Tower of IE: The Wizard Climb**  
2D vertical platformer built with Python and Pygame, playable in-browser via WebAssembly (Pygbag). Climb a tower by conjuring platforms in real time, with physics, collision detection, camera scrolling, and a JSON-based leaderboard. Modular OOP architecture.  
`Python · Pygame`  
[GitHub](https://github.com/stefhooy/tower-of-ie-wizard-climb) · [Play it](https://stefhooy.itch.io/tower-of-ie-the-wizard-climb)

---

## Outside the Code

🎵 **Music:** EDM · Rock · Indie · Alternative · Jazz · Disco · 80s Pop · Huge Queen fan  
🏐🏀 **Sports:** Volleyball & Basketball (currently playing basketball in a recreational league in Sofia)  
📷🎬 Also into photography and video editing

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stephanpentchev/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:stephan.pentchev@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/stefhooy)

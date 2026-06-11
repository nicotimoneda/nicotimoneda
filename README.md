<div align="center">

# Hi, I'm Nico 👋

**ML Engineer & AI Developer** · Building generative models and multi-agent systems. Spending a lot of time on the boring parts that make them actually ship.

[![Location](https://img.shields.io/badge/-Talavera%20de%20la%20Reina,%20Spain-2E2E2E?style=flat-square&logo=googlemaps&logoColor=white)](https://github.com/nicotimoneda)
[![BSc](https://img.shields.io/badge/-BSc%20Data%20Science%20%26%20AI-2E2E2E?style=flat-square&logo=academia&logoColor=white)](https://www.uax.com)
[![Available](https://img.shields.io/badge/Open%20to%20work-mid--2026-1A7F37?style=flat-square)](mailto:nicotimoneda@gmail.com)

</div>

---

### What I'm doing right now

- 🛠️ **AI Developer** at **NTT Data**, working on LLM orchestration and tool-use patterns for real enterprise workflows
- 🎓 **BSc in Data Science & AI** at **Universidad Alfonso X el Sabio (UAX)** — thesis submitted, graduating June 2026
- ✍️ Writing about ML engineering on [**Substack**](https://nicotimoneda.substack.com) — honest validation, negative results included
- 🔎 Looking for **full-time ML Engineer / AI Developer roles**, remote or hybrid out of Madrid

---

### Tech I work with

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" />
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img alt="Pandas" src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img alt="SQL" src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="Azure" src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
</p>

**Generative AI & LLMs:** LangChain · LangGraph · Multi-Agent Systems · RAG · Gemini 2.0 Flash · OpenAI API
**Deep Learning:** PyTorch · TensorFlow · WGAN-GP · LSTMs · CNNs · Transformers
**Classical ML:** Scikit-learn · XGBoost · Random Forest · Logistic Regression · K-Means · KNN · Ensemble Methods
**Engineering:** Python · SQL · Docker · GitHub Actions · uv · Streamlit · Git

---

### Things I've built

#### 🎓 [TFG_MultiAgente](https://github.com/nicotimoneda/TFG_MultiAgente) · *Final-Year Thesis*
Controlled experiment on whether **multi-agent LLM pipelines** actually beat a single model at code generation. 1,476 runs on HumanEval, paired McNemar tests, full cost accounting. Finding: the single-model baseline wins — **80% vs 58% pass@1 at 1/40th the token cost**. The hard part isn't the agents — it's having the rigour to report that they didn't help.
`LangGraph` · `Ollama` · `Statistical Testing` · `Python`

#### 🧪 [SyntheticMarket-GAN](https://github.com/nicotimoneda/SyntheticMarket-GAN) · *Generative Time Series · CI'd Package*
**WGAN-GP** for synthetic AAPL price windows, refactored from notebook into an installable, tested package (pytest + ruff + GitHub Actions). PCA/t-SNE show strong real/synthetic overlap, but the honest headline — written up [on Substack](https://nicotimoneda.substack.com/p/wgan-gp-on-aapl-when-pca-looks-fine) — is that **step-to-step volatility comes out 4× too high**, a failure mode PCA and t-SNE silently miss.
`PyTorch` · `WGAN-GP` · `pytest` · `GitHub Actions`

#### 🤖 [Travel Planner AI](https://github.com/nicotimoneda/travel-planner-ai) · *Multi-Agent System*
Two specialised agents on a **LangGraph** state machine: a low-temperature *Explorer* doing live web research, a *Planner* turning it into day-by-day itineraries with budgets, and conditional error routing between them so a failed search never becomes a hallucinated plan. **Gemini 2.0 Flash** + Streamlit.
`LangGraph` · `Gemini 2.0` · `Streamlit` · `Python`

#### ⚽ [Player Similarity Finder](https://github.com/nicotimoneda/PlayerSimilarityFinder) · *Sports Analytics App*
Unsupervised scouting tool over **2,700+ players** from Europe's Big 5 leagues. K-Means tactical profiles + a KNN similarity engine with explainable scores — query Lamine Yamal, get Wirtz, Olise and Barcola with radar-chart evidence. Live Streamlit app, screenshots in the repo.
`Scikit-learn` · `K-Means` · `KNN` · `Streamlit`

#### 📊 [Customer Churn Prediction](https://github.com/nicotimoneda/Customer-Churn-Prediction) · *Classification, Honest Benchmark*
Four classifiers benchmarked on imbalanced Telco churn data with GridSearchCV — and the simple model won: **Logistic Regression beats tuned XGBoost on recall (0.572 vs 0.505) with 25 fewer missed churners**. Model selection driven by the business cost of false negatives, not leaderboard accuracy.
`Scikit-learn` · `XGBoost` · `GridSearchCV`

---

### 📊 GitHub stats

<div align="center">

<a href="https://github.com/nicotimoneda">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=nicotimoneda&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nicotimoneda&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" />
</a>

<br/>

<a href="https://github.com/nicotimoneda">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nicotimoneda&theme=tokyonight&hide_border=true" />
</a>

</div>

---

### Certifications

- ✅ **Introduction to Generative AI** — Google Cloud Skills Boost
- ✅ **Introduction to Large Language Models** — DeepLearning.AI
- ✅ **Elements of AI** — University of Helsinki
- 🔄 **IBM AI Engineering** & **Microsoft Azure AI** — *in progress*

---

### 📫 Reach me

- 📧 [nicotimoneda@gmail.com](mailto:nicotimoneda@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/nicol%C3%A1s-timoneda-mart%C3%ADnez/)
- 📍 Talavera de la Reina, Spain
- 🌐 Languages: 🇪🇸 Spanish (native) · 🇬🇧 English (C1) · 🇫🇷 French (B2)

---

<div align="center">
  <sub>"Build the boring infrastructure that lets the interesting things ship."</sub>
</div>

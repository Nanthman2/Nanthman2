<!-- =======================
PROFILE README (GitHub)
Nathan Devaux — Junior Data Scientist
======================= -->

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:22c55e&height=180&section=header&text=Nathan%20Devaux&fontSize=48&fontColor=ffffff&animation=twinkling&desc=Junior%20Data%20Scientist&descAlignY=72" alt="Nathan Devaux banner" />
</p>

<p align="center">
<a href="mailto:nathandevaux0309@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-informational" alt="email badge"/>
</a>
<a href="https://www.linkedin.com/in/nathan-devaux-5a209b352/">
<img src="https://img.shields.io/badge/LinkedIn-Profile-informational" alt="linkedin badge"/>
</a>
<img src="https://img.shields.io/badge/Location-Belgium-informational" alt="location badge"/>
</p>

---

## 👋 About me

I'm **Nathan Devaux**, a **Junior Data Scientist** with an **M.Sc. in Data Science & Applied Statistics from UCLouvain**.

I enjoy building **end-to-end projects**: data understanding → modeling → validation → communication (reports & interactive apps).

**Interests:** Machine Learning, Artificial Intelligence, High-Dimensional Data Mining, Causal Inference.

---

## 🛠️ Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

**Data & Machine Learning**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=for-the-badge)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-2C64C6?style=for-the-badge)

**Big Data**

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

**Visualization & Apps**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## ⭐ Featured projects

### 📈 Grocery Retail Dashboard — Streamlit Stock Tracker
**Goal:** track European grocery retail stocks with live price history, technical indicators, and optional AI-generated commentary.

**Highlights**
- Interactive candlestick charts (SMA20/SMA50, RSI) via Plotly
- Fundamental ratio comparison across peers (P/E, P/B, ROE, Debt/Equity, dividend yield)
- Optional LLM commentary with Groq → Gemini fallback, 100% free stack

**Repo:** [grocery-retail-dashboard](https://github.com/Nanthman2/grocery-retail-dashboard)

---

### 🎲 Markov Decision Processes — *Snakes & Ladders* (Value Iteration)
**Goal:** learn an **optimal policy** (dice choice) in a stochastic environment with traps/boosts.

**Highlights**
- Formalized the game as an **MDP**
- Solved with **Value Iteration** (Bellman updates)
- Validated via simulations and baseline comparisons

**Repo:** [mdp_snakes_ladders](https://github.com/Nanthman2/university-projects/tree/main/MachineLearning_projects/Master%201/Data%20Mining%20and%20Decision%20Making/Project_1)
**Report:** [LINFO2275_Project_1.pdf](https://github.com/Nanthman2/university-projects/blob/main/MachineLearning_projects/Master%201/Data%20Mining%20and%20Decision%20Making/Project_1/LINFO2275_Project_1.pdf)

---

### 🧠 Machine Learning — *Smurfs* (Heart failure risk prediction)
**Goal:** predict a clinical risk score from structured data (project includes an image component).

**Highlights**
- Leakage-safe preprocessing + end-to-end pipelines
- Compared multiple models and tuned hyperparameters (Optuna)
- Clear evaluation and model selection

**Repo:** [heart_failure_ml](https://github.com/Nanthman2/university-projects/tree/main/MachineLearning_projects/Master%202/Machine%20Learning)
**Report:** [LELEC2870___Machine_learning_FinalSubmission.pdf](https://github.com/Nanthman2/university-projects/blob/main/MachineLearning_projects/Master%202/Machine%20Learning/LELEC2870___Machine_learning_FinalSubmission.pdf)

---

### 📌 Bayesian Hierarchical Modeling — Poisson + Random Effects (Hospitals)
**Goal:** model count data with **patients nested within hospitals** using hierarchical Bayes.

**Highlights**
- Poisson regression + Gamma random effects (and variants)
- Implemented **MCMC from scratch** (Gibbs when possible + Metropolis RW otherwise)
- Posterior summaries + convergence/diagnostic checks

**Repo:** [bayesian_hierarchical_mcmc](https://github.com/Nanthman2/university-projects/tree/main/Statistical_projects/Master%201/Bayesian_statistics)
**Report:** [VanWymeersch-Piron-Devaux (1).pdf](https://github.com/Nanthman2/university-projects/blob/main/Statistical_projects/Master%201/Bayesian_statistics/VanWymeersch-Piron-Devaux%20(1).pdf)

---

### 🧬 Interactive Dashboard — Breast Cancer Genomics (METABRIC)
**Goal:** make high-dimensional genomics exploration **interactive and accessible**.

**Highlights**
- EDA + differential expression (Volcano Plot)
- **PCA / UMAP** + neighborhood-preservation metrics
- Clustering: K-means, hierarchical, DBSCAN + cluster validity metrics

**Repo:** [dashboard_LDATA2010](https://github.com/Nanthman2/university-projects/tree/main/Visualisation_project/dashboard_LDATA2010)
**App:** [app.py](https://github.com/Nanthman2/university-projects/blob/main/Visualisation_project/dashboard_LDATA2010/app.py)
**Report:** [LDATA2010__PROJECT__PIRON_DEVAUX.pdf](https://github.com/Nanthman2/university-projects/blob/main/Visualisation_project/dashboard_LDATA2010/report/LDATA2010__PROJECT__PIRON_DEVAUX.pdf)

---

### 🌡️ Time Series — Nottingham Monthly Temperatures (1920–1939)
**Goal:** capture seasonality and forecast with **SARIMA**, benchmarked against **Holt–Winters**.

**Highlights**
- Seasonal differencing, ACF/PACF identification, AIC model comparison
- Residual diagnostics (e.g., Ljung–Box) + prediction intervals

**Repo:** [time_series_nottingham](https://github.com/Nanthman2/university-projects/tree/main/Statistical_projects/Master%201/TimeSeries)
**Report:** [Time_series.pdf](https://github.com/Nanthman2/university-projects/blob/main/Statistical_projects/Master%201/TimeSeries/Time_series.pdf)

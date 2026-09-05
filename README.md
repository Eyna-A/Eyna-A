

<div align="center">

<img src="./assets/24cd0715-3651-42eb-b3f7-376c433f4fef.jpg" alt="Header Banner" width="100%"/>

<a href="https://github.com/Eyna-A">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00F0FF&center=true&vCenter=true&width=650&height=50&lines=AI+Builder+%26+0-to-1+Founder;Shipping+Production-Grade+ML+Systems;Autonomous+Agents+%26+Quant+Pipelines" alt="Typing SVG" />
</a>

<b>I build AI products that ship — and hold up once real users (and real money) touch them.</b>

<a href="mailto:eynashabani@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Badge"/></a>
<a href="https://linkedin.com/in/eyna-shabani-a05933283"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/></a>
<a href="https://github.com/Eyna-A"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/></a>

</div>

---

### ⚡ About Me

- 🚀 **Builder first:** I take AI ideas from 0 → 1 — research prototype to a deployed product with a real API, dashboard, and users.
- 🧪 **Diagnostics before hype:** every model ships with the validation I'd want to see as an investor — leakage checks, regime-shift tests, and honest metrics, not just a nice-looking demo.
- 🔬 **Core stack:** deep learning, autonomous agent systems (LangChain/LangGraph), and quantitative research pipelines — applied to markets and products that punish shortcuts.
- 🎧 **Off the clock:** I chase the same pattern-finding instinct in music that I do in markets and models.

---

### 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white)

**Frameworks**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/Keras%2FTensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) ![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-FF0055?style=for-the-badge&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

**MLOps / Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-00F0FF?style=for-the-badge&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-111111?style=for-the-badge&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

---

### 🌟 Spotlight Project — [Signal Desk: TSE Robo-Advisor](https://github.com/Eyna-A/tse-signal-desk)

*An end-to-end ML pipeline for the Tehran Stock Exchange, built around one rule: never trust a Sharpe ratio you haven't tried to disprove.*

**The problem.** Most "AI stock picker" projects publish a flattering equity curve and stop there. Emerging-market data makes that dangerous fast: non-stationary nominal prices, capital increases that crater a ticker >30% overnight with zero economic loss, and multi-month trading halts that can still look like a "buy" if nobody checks for staleness.

**What I built.**
- Full pipeline — ingestion → feature engineering → LightGBM training → backtesting → live inference → portfolio optimization → dashboard — running end-to-end on CPU.
- Four independent signal-validity diagnostics (mutual information, regime-shift, ticker-leakage, cross-sectional variance decomposition) gate every feature before it's trusted, not after a backtest looks good.
- Strategy evaluation via **Deflated Sharpe Ratio**, which explicitly corrects for selection bias — so the headline number can't be gamed by trying enough configs.
- Market-specific engineering: automatic capital-increase adjustment, halt/staleness filtering, dollar-relative normalization, and an independent geopolitical risk brake.
- A bilingual (FA/EN), dark/light, zero-build FastAPI + vanilla-JS dashboard — no npm, no bundler, one origin.

**Key tech:** `Python` · `LightGBM` · `FastAPI` · `scikit-learn` · `SciPy` · `SQLite` · `Chart.js`

**Why it matters.** The latest full run reports a Deflated Sharpe Ratio of 0.221 — below the threshold for statistical significance — and the README leads with that, in bold, on the front page. For a founder, that's the actual deliverable: the discipline to publish a negative result instead of a cherry-picked one, and the engineering judgment to know the difference before it costs a user real money.

---

<div align="center">
<sub>Designed & built by <b>Eyna Shabani</b> · B.Sc. Computer Science, Islamic Azad University, Tehran West Branch</sub>
</div>

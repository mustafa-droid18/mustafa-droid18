<div align="center">

# Mustafa Poonawala

**MS in Data Science @ NYU** (GPA 3.9/4.0) · Published researcher · ML for credit risk, reinforcement learning, and LLM systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mustafa1808-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mustafa1808/)
[![Email](https://img.shields.io/badge/msp9471%40nyu.edu-D14836?logo=gmail&logoColor=white)](mailto:msp9471@nyu.edu)
![Location](https://img.shields.io/badge/New%20York,%20NY-2ea44f)

I build ML systems with measurable results — calibrated probabilities, backtested pipelines, benchmarked agents.

</div>

## Featured Projects

### [Credit-Risk-Corporate-PD](https://github.com/mustafa-droid18/Credit-Risk-Corporate-PD)

> XGBoost default-probability model on 1M+ firm-year records with isotonic calibration — decision-usable, auditable outputs for corporate default prediction.

- **Walk-forward AUC 0.837** on time-validated data, using finance-grounded features (Altman Z, leverage, liquidity)
- Packaged as a CLI scoring harness with persisted artifacts (model, calibrator, metadata) for reproducible inference

### [LLM-Reward-Shaping](https://github.com/mustafa-droid18/LLM-Reward-Shaping)

> Can an LLM replace a human reward engineer? An automated Claude loop that designs and revises PPO reward functions on Super Mario Bros.

- **Matched 74.5% of an expert's hand-tuned 8-iteration result in just 5 fully automated rounds**
- Revises rewards using training diagnostics (entropy, episode length, explained variance) as feedback
- Caught reward-hacking exploits and two evaluation bugs via methodology audits; rebuilt the comparison on a leak-free criterion

### [RateMyProfessor-Bias-Analysis](https://github.com/mustafa-droid18/RateMyProfessor-Bias-Analysis)

> Gender bias analysis across 90k+ instructor reviews with rigorous statistics.

- Surfaced a statistically significant pro-male rating bias (Mann-Whitney U on Bayesian-adjusted ratings, bootstrap CIs) — and showed it is practically negligible (Cliff's Δ ≈ 0.04)
- Found 18 of 20 student tags significantly gendered; modeled ratings (test R² = 0.79) and “pepper” status (AUROC = 0.94)

### [Air-Pollution-Prediction-with-Advanced-Preprocessing-and-Deep-Ensemble-Learning](https://github.com/mustafa-droid18/Air-Pollution-Prediction-with-Advanced-Preprocessing-and-Deep-Ensemble-Learning) — 📄 *Atmospheric Pollution Research, 2025*

> BiLSTM + XGBoost weighted ensemble forecasting hourly PM2.5 from a 48-hour lookback.

- **R² = 0.89** on 30k+ samples, outperforming individual-model baselines under strict temporal validation
- Reusable preprocessing pipeline with PPCA imputation and robust scaling

### [Solving-the-0-1-Knapsack-Problem-Using-the-LAB-Algorithm](https://github.com/mustafa-droid18/Solving-the-0-1-Knapsack-Problem-Using-the-LAB-Algorithm) — 📄 *Springer Handbook of Formal Optimization, 2024*

> LAB (Leader–Advocate–Believer) metaheuristic with constraint-repair and stagnation-triggered perturbation.

- Reached known optima on **19/20 single-knapsack** and **20/30 multidimensional WEISH** benchmarks (remaining gaps < 0.7%)
- Shipped as a reproducible Python package with automated tests and CLI benchmarking

### [Scribee](https://github.com/mustafa-droid18/Scribee)

> Sign language & Braille translation app for accessibility — led the team shipping it end to end.

- Real-time hand-sign recognition (MediaPipe + TensorFlow) integrated with speech recognition and a Streamlit UI

## Publications

1. Narkhede, G.G., **Poonawala, M.**, et al. [*Air Pollution Prediction with Advanced Preprocessing and Deep Ensemble Learning*](https://doi.org/10.1016/j.apr.2025.102610). *Atmospheric Pollution Research*, 2025.
2. **Poonawala, M.**, Kulkarni, A. [*Solving the 0-1 Knapsack Problem Using LAB Algorithm*](https://doi.org/10.1007/978-981-97-3820-5_59). *Handbook of Formal Optimization*, Springer, 2024.
3. **Poonawala, M.**, et al. [*LoRa-Based Farm Monitoring System*](https://doi.org/10.1007/978-981-99-6568-7_25). *ICT Analysis and Applications*, Springer, 2023.

## Skills

|  |  |
| --- | --- |
| **Languages** | Python · SQL · Java · C++ · R |
| **ML / AI** | scikit-learn · XGBoost · PyTorch · TensorFlow · Transformers · HuggingFace · NLP · Computer Vision |
| **Generative AI** | LangGraph · Claude · GPT-4o · LLM-as-judge evaluation · prompt engineering · agent orchestration |
| **Statistics & Modeling** | Hypothesis testing · Bayesian inference · bootstrap resampling · walk-forward validation · probability calibration · time series |
| **Tools** | pandas · NumPy · Streamlit · Tableau · Power BI · AWS · Spark · Git |

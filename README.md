# Hi, I'm Tolbert (Osus)

**Mathematics & Computer Science graduate (Multimedia University of Kenya, Class of 2026). I build health-tech products and test quant trading ideas with strict statistics.** Based in Nairobi.

I like problems where getting the numbers right actually matters: a child's breathing sounds, a patient's blood pressure, or whether a trading "edge" is real or just noise.

---

### Health-tech for Kenya

| Project | What it is | Stack |
|---|---|---|
| [**SautiYaAfya**](https://github.com/Tolbert-Okoth/sauti-ya-afya) | Lung-sound screening for community health workers. A MobileNetV2 model flags crackles and wheeze in a child's chest recordings, then WHO IMCI rules set the referral level. **72% accuracy on 129 held-out patients**; per-child crackle detection 0.79 sensitivity / 0.76 specificity. | PyTorch, torchaudio, FastAPI, React |
| [**TunzaCare**](https://github.com/Tolbert-Okoth/TunzaCare) | Offline-first companion for adults managing hypertension or type 2 diabetes. Every clinical cutoff traced to ISH 2020 / ADA 2024 / Kenya MoH guidelines; English + Kiswahili; 23/23 tests covering clinical boundaries and privacy rules. | Vanilla JS, Node test runner |
| [**Afya-Pulse**](https://github.com/Tolbert-Okoth/afya-pulse) | Real-time triage and outbreak dashboard. An LLM sorts symptom reports (English, Swahili, Sheng) into red/yellow/green; doctors see cases live. | React, Node/Express, Socket.io, Flask, PostgreSQL |

### Quantitative research & tooling

| Project | What it shows |
|---|---|
| [**propsim**](https://github.com/Tolbert-Okoth/propfirm-pass-sim) | Monte Carlo simulator for 17 prop-firm challenges (numba, 3,000 paths in about 0.1 s). Finding: a strategy with **zero edge passes FTMO about 29% of the time** at sensible risk, against roughly 10% reported for real traders. Checked against the optional stopping theorem. |
| [**dukafetch**](https://github.com/Tolbert-Okoth/dukascopy-tools) | Resumable downloader and verified decoder for free Dukascopy tick data. Shows that an optimistic bar backtest can turn a losing strategy (−0.47 R per trade on ticks) into a "winning" one (+0.12 R). |
| [**vprofile**](https://github.com/Tolbert-Okoth/volume-profile-toolkit) | Look-ahead-free volume profiles. Validated against ~800,000 COMEX gold trades: free 5-minute bars reproduce the tick profile (0.987 median shape correlation), but candle-colour "delta" is noise. |
| [**RV15 Forecasting Engine**](https://github.com/Tolbert-Okoth/rv15-forecasting-engine) | 15-minute realised-variance forecasting with an append-only forecast ledger. A HAR model improved QLIKE over EWMA by 23% across 68,291 forecasts. |
| [**Hurst/DFA Regime Classifier**](https://github.com/Tolbert-Okoth/Gold--hurst--daily-classifier) | Pre-registered test of whether Hurst exponents predict gold returns, on 16 years of data. Passed estimator calibration, then **killed** by permutation nulls, regime splits and outlier trimming. |

**How I do research:** write the hypothesis and kill criteria first, calibrate on synthetic data, test against shuffled and random-walk nulls, check every regime, and report results that fail.

---

### Tools

**Languages:** Python · JavaScript · SQL
**Data & ML:** pandas · NumPy · numba · PyTorch · XGBoost · Optuna · Monte Carlo simulation · statistical testing
**Web:** React · Node.js/Express · FastAPI · Flask · PostgreSQL · Firebase · Supabase
**Deploy:** Vercel · Render · Neon

### Contact

[LinkedIn](https://www.linkedin.com/in/tolbert-asumba-542b3b344) · Open to data science, health-tech and quant roles, and to freelance work.

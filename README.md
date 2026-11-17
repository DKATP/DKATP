# Diana Pedraza

**Economist and data scientist.** I build decision systems: the layer that turns models and business rules into a concrete answer about which customer gets which action, and whether that action should happen at all.

Six years across telecom, banking, insurance and pharma, mostly as the bridge between a business problem nobody has framed yet and a pipeline somebody has to maintain afterwards.

---

### What I care about

- **Causal questions over predictive ones.** Who buys is easier than who buys *because* we contacted them. The second question is usually the one worth money.
- **Silent failures are worse than errors.** A pipeline that stops is annoying; a pipeline that quietly scores the wrong population for a week is expensive.
- **Rules belong in tables, not in code.** If a business owner cannot change a threshold without a deployment, the system is not finished.
- **Saying what I did not do.** Separating what was built from what was designed from what was never validated is what makes the rest credible.

---

### Featured work

**[Next-Best-Action Engine](https://github.com/DKATP/Next-Best-Action_Engine)** — a decision engine for a telecom, on fully synthetic data.

Decides which offer each customer gets, through which channel, and whether contacting them is prudent at all. Three layers, each answering a different question:

| Layer | Question | Methods |
|---|---|---|
| Decision engine | What should we offer? | Staged pipeline, stop-on-failure data gates, editable rule tables, quota distribution with a randomized control group |
| Propensity & uplift | Who buys *because* we contacted them? | Logistic regression vs. gradient boosting, grouped cross-validation, calibration, two-model uplift, AUUC |
| Lifetime value | What is this customer worth? | Kaplan-Meier, Cox with a Schoenfeld test and C-index, BG/NBD and Gamma-Gamma for the prepaid base |

Validated by parameter recovery: the synthetic generators have known true parameters, and the estimators recover them. 63 tests, CI on two Python versions.

---

### Background

| | |
|---|---|
| **Telecom** | Next-best-action engine on Databricks: discovery across business units, architecture, data-quality controls, pilot design with treatment and control groups. Independent review of other teams' models before integrating them. |
| **Insurance / construction** | Customer risk-scoring model adopted for delivery decisions, with MLflow in production. Technical lead of a WhatsApp conversational agent built on an LLM, focused on answer quality and reducing hallucinations. **Grupo Bolívar Innovation Award, 2023.** |
| **Banking** | Anti-fraud analytics — balancing detection against the cost of false positives. |
| **Pharma** | Financial reporting. |

Economist by training, with an emphasis on policy and international relations. Master's in progress.

---

### Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

Survival analysis · uplift modelling · experiment design · data-quality engineering

---

📍 Bogotá, Colombia · open to remote roles

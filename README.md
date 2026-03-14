# global-gourmet
# Vanguard Sovereign: Multi-Stage Logistics & Predictive Risk Engine
### Lead Data Science Taskforce | Ingenium - IIT Indore

**Vanguard Sovereign** is an end-to-end predictive architecture designed to solve the "Golden Table" problem in urban logistics. Developed for the Global Gourmet Challenge, this system bridges the gap between raw spatio-temporal telemetry and high-level economic optimization.

---

## 📊 Performance Benchmarks
| Metric | Result | Engineering Significance |
| :--- | :--- | :--- |
| **ETA Precision ($R^2$)** | **0.94** | Captures 94% of grid complexity under 10% stochastic noise. |
| **Churn Risk (AUC-ROC)** | **0.95** | Near-perfect separation of at-risk vs. satisfied user segments. |
| **MAE (Mean Absolute Error)** | **0.96 min** | Sub-minute delivery estimation accuracy. |
| **RMSE** | **1.39 min** | High stability against "Black Swan" outlier events (>2SD). |

---

## 🛠️ System Architecture

### Layer 1: The GeoPhysics Engine (Logistics)
* **Infrastructure Mapping:** Integrated `OSMnx` for `.graphml` urban grid abstraction, incorporating lane density and traffic light frequency.
* **Temporal Synchronization:** Aligned real-time **Weather "Taxes"** (Precipitation/Visibility) with order timestamps to quantify "Travel Decay."
* **Robustness Testing:** Injected 10% Gaussian noise into the feature set to ensure the model learned underlying grid physics rather than sensor drift.

### Layer 2: The Sentiment Engine (NLP)
* **Grievance Taxonomy:** Deployed **Latent Dirichlet Allocation (LDA)** to identify four core pillars of brand erosion: *Systemic Lateness, Thermal Loss, Order Accuracy, and Professionalism.*
* **Causal Explainability:** Utilized **SHAP (Shapley Additive Explanations)** to prove that `VOC_max` (Congestion) is the mathematically dominant cause of 1-star reviews.

### Layer 3: Predictive Risk & Revenue Optimization
* **The "Moral Veto":** A logistic regression-based "Safety Valve" that proactively disables surge pricing for high-risk segments to maintain a strict **2% Churn Constraint**.
* **Equilibrium Pricing:** Strategically balanced 25% potential revenue gains against predicted Customer Lifetime Value (CLV) protection.

---

## 📂 ETL & The "Golden Table"
* **Entity Resolution:** Resolved duplicate entries and inconsistent SQL transactional logs.
* **Feature Alignment:** Merged heterogeneous sources (SQL, JSON, CSV) into a unified high-fidelity matrix.
* **Outlier Management:** Specifically optimized for extreme lateness cases (Outliers > 2 Standard Deviations) as per the 2SD Audit requirements.

---

## 🔮 Future Scope: The Stanford Bridge
Current validation uses high-performance Gradient Boosting (XGBoost). The v2.0 roadmap includes:
* **Temporal Fusion Transformers (TFT):** Utilizing Attention Mechanisms to capture global city-wide traffic ripples.
* **Zero-ID Profiling:** Enhancing privacy-first churn prediction without utilizing PII.

---

## 👨‍💻 Author
**Ram Upadhyay** *Computer Science Engineering, IIT Indore* *Rank Opener | Machine Learning Specialist*

---
## 📜 License
Developed for the Ingenium 2026 Competition. All rights reserved.

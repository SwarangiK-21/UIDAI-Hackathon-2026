# 👁️ Project Drishti: Strategic Governance Dashboard for Aadhaar

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Status](https://img.shields.io/badge/Status-Hackathon%20Submission-success)
![Focus](https://img.shields.io/badge/Focus-Social%20Justice%20%7C%20Geopolitics-orange)

**Project Drishti** is a comprehensive Data Science framework designed to transition UIDAI from a *System of Record* to a *System of Intelligence*. By analyzing anonymized spatiotemporal metadata, we identify critical governance gaps—from "Biometric Burnout" in manual laborers to "Climate-Induced Enrolment Dips."

---

## 🚀 Key Innovations

### 1. 🔥 The "Biometric Burnout" Detector (Social Justice)
* **Problem:** Manual laborers (farmers, miners) suffer from "Fingerprint Fade," leading to high authentication failure rates and repeated, futile biometric updates.
* **Solution:** We calculate the **Biometric Distress Ratio (BDR)**. Districts with `BDR > 100%` (more updates than people) are flagged as "Red Zones" requiring immediate deployment of **Iris Scanners**.
* **Impact:** Reduces exclusion errors for the poorest beneficiaries.

### 2. 🌍 The "Trade War" Migration Monitor (Geopolitics)
* **Problem:** Post-2025 global trade policies ("Make in India 2.0") are driving unpredicted labor migration to industrial belts (Gujarat, Maharashtra).
* **Solution:** Our **Migration Magnet Index** tracks spikes in *Address Updates* vs. *New Enrolments* to predict housing and PDS (Ration) stress in real-time.

### 3. 🌪️ Climate-Resilient Enrolment (Disaster Mgmt)
* **Problem:** Floods in regions like Assam cause massive enrolment outages ("Disaster Dips").
* **Solution:** Correlation analysis between Monsoon intensity and Enrolment volume triggers automated dispatch of **Mobile Aadhaar Vans** post-disaster.

---

## 📊 Technical Architecture

### Data Pipeline (ETL)
* **Ingestion:** Automated batch processing of sharded CSV files using `glob`.
* **Cleaning:** Imputation of missing values (Null $\rightarrow$ 0) to maintain time-series continuity.
* **Storage:** Optimized Pandas DataFrames for in-memory processing of **5 Million+ records**.

### Analysis & Modeling
* **Anomaly Detection:** Z-Score Statistical testing ($\sigma > 3$) to flag fraud or operational spikes (e.g., East Delhi Anomaly).
* **Forecasting:** Exponential Smoothing (Rolling Averages) for predicting kit demand.
* **Visualization:** Interactive Plotly charts for granular district-level insights.

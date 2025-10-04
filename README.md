# 🌌 Smart Telescope Assistant – Exoplanet Detection & Habitability Analysis

> **A hybrid Computer Vision + Machine Learning pipeline that detects exoplanets from telescope data and ranks them by their potential habitability.**

---

## 🪐 Overview

The **Smart Telescope Assistant** is an AI-powered system that helps astronomers and researchers:
- Detect potential exoplanets from raw telescope light-curve data.
- Analyze their **habitability**, **Earth similarity**, and **atmospheric potential**.
- Rank candidates for **follow-up telescope missions**.

Unlike traditional models that *only detect planets*, this project also provides **scientific prioritization**, helping scientists focus on planets most likely to support life.

---

## 🔭 Pipeline
Raw Light Curve / Telescope Data
│
▼
🧹 Preprocessing / Denoising

Normalize flux & remove noise

Interpolate missing points
│
▼
🧠 Computer Vision (CNN)

Detect U-shaped transit patterns

Classify: Exoplanet / False Positive / Noise
│
▼
📊 Feature Extraction

Transit depth, duration, period

Stellar temperature, radius, luminosity
│
▼
🤖 ML Scoring & Predictive Analysis

Habitability Score (habitable zone probability)

Earth Similarity Index (ESI)

Atmospheric Potential (biosignature likelihood)
│
▼
🔥 Candidate Ranking & Visualization

Rank by detection confidence + habitability

Heatmaps for CNN interpretability
│
▼
🔬 Target Selection for Follow-up Missions

Prioritize top-ranked exoplanets for further observation

\



🌟 Outputs

✅ List of detected exoplanet candidates

🌎 Habitability & Earth Similarity scores

🧠 Heatmaps showing where CNN focused attention

📊 Ranked summary for telescope follow-up


🧑‍💻 Contributors(till now)

[Prashansha Rawat] – Project Lead / Idea / Model Development/research

[Contributors] 

1.Raju Kushwaha– frontend (streamlit)

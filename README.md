# Mini GlucoNet-MM  
**Multimodal, Explainable, and Uncertainty-Aware Blood Glucose Forecasting for Personalized Healthcare**

![Home](./Home.png)

## Overview

This repository presents a **research-oriented prototype** exploring **multimodal** and **explainable machine learning** for personalized **blood-glucose prediction** in diabetes care.

The project is motivated by emerging directions in:

- Uncertainty-aware AI for healthcare  
- Self-adaptive intelligent systems  
- Multimodal physiological data modeling  
- Interpretable clinical decision support  

These themes closely relate to current research in **AI-driven healthcare** and **intelligent adaptive systems**.

---

## Research Motivation

Accurate glucose prediction alone is **not sufficient** for real-world clinical deployment.

Healthcare AI systems must also provide:

- **Interpretability** for clinician trust  
- **Personalization** across patient variability  
- **Robustness** under uncertain physiological signals  
- **Adaptive decision support** over time  

This prototype explores these challenges through a **compact experimental framework**.

---

## What This Prototype Demonstrates

### 1. Multimodal Healthcare Learning
Integration of multiple physiological signals:

- Continuous glucose monitoring (CGM)  
- Insulin dosage  
- Carbohydrate intake  

to model **temporal metabolic dynamics**.

### 2. Explainable Temporal Modeling
Use of:

- **GRU-based sequence encoder**  
- **Attention mechanism**  

to highlight **clinically relevant time steps** influencing predictions.

### 3. Short-Term Personalized Forecasting
Prediction of **future glucose trajectories** tailored to **individual patient patterns**.

### 4. Initial Uncertainty Awareness *(Research Direction)*
Exploration toward:

- Prediction confidence estimation  
- Robustness under noisy physiological data  
- Reliability for safety-critical healthcare AI  

This connects to broader research on **uncertainty in intelligent systems**.

---

## Method Overview

- Normalize multimodal physiological **time-series data**  
- Encode temporal dynamics using **GRU**  
- Apply **attention** for interpretability  
- Predict **short-term glucose levels**  
- Visualize:
  - Prediction curves  
  - Training loss  
  - Attention heatmaps  

---

## Key Learning Outcomes

This work enabled practical understanding of:

- Multimodal healthcare **ML pipeline design**  
- **Interpretable temporal deep learning**  
- **Personalization** in clinical AI systems  
- Challenges of **uncertainty and reliability** in medical prediction  

---

## Relevance to Ongoing Research Directions

This prototype conceptually aligns with research themes in:

- Uncertainty-aware AI for **real-world data**  
- **Self-adaptive intelligent systems**  
- AI for **healthcare monitoring and decision support**  
- **Interpretable and trustworthy machine learning**  

and serves as an **initial exploratory step** toward **research-level healthcare AI systems**.

---

## Future Research Extensions

Planned next steps include:

- Evaluation on real clinical datasets *(e.g., OhioT1DM, BrisT1D)*  
- **Multi-horizon glucose prediction** (multi-task learning)  
- Integration of **decision-transformer-style policy modeling**  
- Improved **uncertainty quantification and explainability**  
- Progression toward **adaptive, patient-specific decision support**  

---

## Author

**Sajjad Ahmad**  
BS Computer Science *(Expected July 2026)*  

**Research Interests:**

- Multimodal AI  
- Explainable Healthcare Machine Learning  
- Uncertainty-Aware Intelligent Systems  
- Personalized Clinical Decision Support  

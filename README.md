# Emotion-Aware Content Optimization (Neuromarketing Research Project)

> Interdisciplinary Research Initiative – University of Illinois Urbana-Champaign  
> *Bridging Neuroscience, Advertising, and Artificial Intelligence to model user emotions and improve content personalization.*

---

## Project Overview

Our project explores how emotional responses captured through physiological signals like EEG, heart rate, and eye-tracking can inform content personalization and recommendation systems beyond traditional click or swipe-based data.

We are developing a framework that maps multimodal biosignals to emotional states using the PAD (Pleasure–Arousal–Dominance) model, treating it as a regression-based emotional representation rather than categorical classification. By analyzing open-source datasets such as DEAP and Neuma, we aim to extract meaningful emotional features (attention, engagement, and pleasure) and correlate them with content labels (ads, videos, or game stimuli).

The ultimate goal is to design a machine learning pipeline capable of predicting user engagement and optimizing content delivery strategies.

---

## Research Goals

- Develop an emotion-based modeling framework using EEG and physiological datasets.
- Map emotional features (pleasure, arousal, dominance) to content types and engagement metrics.
- Evaluate how emotional signals can enhance personalization, ad relevance, and user satisfaction.
- Bridge behavioral science, advertising theory, and machine learning for neuromarketing applications.

---

## Methodology

1. Literature Review & Foundations
   - Analyze existing neuromarketing and affective computing studies.
   - Study the evolution of the PAD model and its extensions in media research.

2. Dataset Exploration
   - Work primarily with DEAP and Neuma datasets.
   - Preprocess EEG and physiological data: filtering, normalization, signal segmentation.

3. Feature Extraction
   - Compute emotional features such as attention, engagement, pleasure, arousal, and dominance.
   - Apply statistical, frequency, and time-domain analyses.

4. Modeling
   - Build a regression model to map signals → emotional states.
   - Compare PAD-based regression with categorical emotion classifiers.

5. Content Labeling
   - Extract emotional metadata from ad content and stimuli (e.g., valence, intensity).
   - Create generalized emotion tensors linking content and user response.

6. Framework Development
   - Integrate behavioral and technical insights into a hybrid recommendation system.
   - Evaluate results using metrics such as MAE, RMSE, and correlation with self-reported affect.

---

## Team Structure

| Team | Focus Area | Key Responsibilities | Members |
|------|-------------|----------------------|----------|
| **Project Management** | Coordination, Planning, Documentation | - Oversee project timeline and deliverables<br>- Maintain documentation and GitHub updates<br>- Schedule meetings and track milestones<br>- Ensure cross-team communication and integration | Alexia Rendon |
| **Tech & Data Science Team** | Machine Learning, Signal Processing, Modeling | - Dataset preprocessing and feature extraction<br>- PAD model replication<br>- Multimodal emotion regression<br>- Tensor generation and data pipelines | [Anant Goyal](https://github.com/anant248)<br> [Bilal Arif](https://github.com/bilalarif3197) |
| **Behavioral & Strategy Team** | Research Design, Emotion Theory, Human Insights | - Literature review on emotional response frameworks<br>- Cold-start and participant bias mitigation<br>- Data visualization and figure generation<br>- Test scenario planning for emotional measurement | [Vrushi Patel Placeholder]<br>[Name Placeholder] |
| **Faculty Advisor (Pending)** | Research Mentorship & Sponsorship | - Oversight of experimental design and data ethics<br>- Review of PAD modeling methodology<br>- Support for symposium presentation and publication | [To Be Determined] |



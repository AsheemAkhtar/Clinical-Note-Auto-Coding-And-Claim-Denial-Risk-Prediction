# Clinical-Note-Auto-Coding-And-Claim-Denial-Risk-Prediction
AI Platform for Clinical Note Auto-Coding & Claim Denial Risk Prediction

It is a two-module healthcare AI system that automates ICD/DRG code prediction from clinical notes and predicts claim denial risk using structured patient and billing data.
It integrates state-of-the-art NLP transformers and machine-learning models to support revenue cycle management and clinical documentation workflows.
Features
🔹 Module 1 — Clinical Note Auto-Coding (NLP)

Input: Unstructured clinical notes

Output: Predicted ICD/DRG codes

Models used: OpenAI LLM

Tasks supported:

Multi-label classification

Top-K code ranking


🔹 Module 2 — Claim Denial Risk Prediction (ML)

Input: Structured EHR & billing data

gender

Insurance type

Diagnoses & procedures

Length of stay

Previous denial history

Output: High vs Low Denial Risk

Algorithms used: XGBoost

Metrics: AUC, Precision/Recall, F1, Calibration

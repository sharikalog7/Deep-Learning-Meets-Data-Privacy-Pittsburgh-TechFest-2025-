# Differential-Privacy

A comprehensive collection of resources, codebases, and tutorials for learning and applying Differential Privacy (DP) — from foundational theory to state-of-the-art implementations in modern machine learning.

## 🔍 Overview

Differential Privacy (DP) is a mathematical framework for quantifying and limiting privacy risks when analyzing or sharing data. It ensures that the inclusion or exclusion of a single individual's data does not significantly affect the outcome of any analysis — typically achieved by introducing carefully calibrated randomness.

✳️ Core Concepts

Privacy Budgets (ε, δ) — quantify privacy loss and guarantee.

Laplace & Gaussian Mechanisms — foundational methods for adding noise.

Local vs. Central Differential Privacy — trade-offs between client-side and server-side noise addition.

DP-SGD (Differentially Private Stochastic Gradient Descent) — the cornerstone of DP deep learning.

Privacy-Utility Trade-offs — balancing accuracy with privacy guarantees.

🧠 Applications

Secure statistical analysis & data aggregation

Private recommender systems

Federated learning with privacy preservation

Differentially private large language models (LLMs)

Healthcare and sensitive data analytics

🧰 Libraries and Codebases
Library	Language	Description
Google Differential Privacy Library
	C++ / Go / Java	Production-grade tools for aggregate data analysis under DP guarantees.
PipelineDP
	Python	Framework by OpenMined + Google for end-to-end DP pipelines.
IBM Diffprivlib
	Python	Implements DP mechanisms, models, and statistics for research and practical use.
Apple Differential Privacy
	Python	Implements Apple's approach to locally DP data collection.
TensorFlow Privacy
	Python	TensorFlow toolkit for training ML models with DP-SGD and noise accounting.
📘 Tutorials and Example Models
Tutorial	Framework	Description
Flower: Training with Sample-Level Differential Privacy
	TensorFlow	Federated learning + DP example.
TensorFlow Privacy Quickstart
	TensorFlow	Learn DP-SGD and apply privacy accounting.
Example Notebook Topics

Laplace & Gaussian Mechanisms

DP-SGD for Neural Networks

Local DP for client-side anonymization

Privacy vs. Utility demonstrations

## 🎥 Key YouTube Videos & Playlists

Differential Privacy Explained (Security and Privacy Academy)

A Short Introduction to Differential Privacy

Differential Privacy For Machine Learning In Action (with code)

A Course In Differential Privacy (2025, full playlist)

Tutorial on Differential Privacy

SaTML 2023 – Gautam Kamath: An Introduction to Differential Privacy

## 📄 Research Papers & Resources

Differential Privacy in Machine Learning: From Symbolic AI to LLMs (Survey, 2025)

Recent Advances of Differential Privacy in Centralized Deep Learning (Survey)

Google Research: Differential Privacy on Trust Graphs (ITCS 2025)

VaultGemma: State-of-the-Art Differentially Private LLM (2025)

Harvard Privacy Tools: DP Resources

Utrecht University: Data Privacy Handbook

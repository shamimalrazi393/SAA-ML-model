# SAA Catalyst ML Full Process

---

## Table of Contents
Click on any step to jump directly to its section.

<details open>
<summary><b>Expand / Collapse Workflow Steps</b></summary>

1. [Step 1 — Environment Setup](#step-1--environment-setup)
2. [Step 2 — Checkpoint Helper Functions](#step-2--checkpoint-helper-functions)
3. [Step 3 — Load Dataset and Engineer Features](#step-3--load-dataset-and-engineer-features)
4. [Step 4 — Exploratory Data Analysis (EDA)](#step-4--exploratory-data-analysis-eda)
5. [Step 5 — Build Feature Matrix](#step-5--build-feature-matrix)
    - [Step 5b — matminer + CALPHAD Feature Enrichment](#step-5b--matminer--calphad-feature-enrichment)
    - [Step 5c — Clean Combined Feature Matrix](#step-5c--clean-combined-feature-matrix)
    - [Step 5d — Activate Combined Feature Matrix](#step-5d--activate-combined-feature-matrix)
6. [Step 6 — Define All Models](#step-6--define-all-models)
7. [Step 7 — Metric Helper Functions](#step-7--metric-helper-functions)
8. [Step 8 — Five-Fold Cross-Validation (RF, DF, MLP)](#step-8--five-fold-cross-validation-rf-df-mlp)
    - [Step 8b — XGBoost Baseline (5-Fold CV)](#step-8b--xgboost-baseline-5-fold-cv)
    - [Step 8c — Statistical Significance Tests + Confidence Intervals](#step-8c--statistical-significance-tests--confidence-intervals)
9. [Step 9 — Leave-One-Host-Out CV — LOHO (RF, DF, MLP)](#step-9--leave-one-host-out-cv--loho-rf-df-mlp)
    - [Step 9b — XGBoost LOHO-CV](#step-9b--xgboost-loho-cv)
10. [Step 10 — Leave-One-Surface-Out CV — LOSO (RF, DF, MLP)](#step-10--leave-one-surface-out-cv--loso-rf-df-mlp)
    - [Step 10b — XGBoost LOSO-CV](#step-10b--xgboost-loso-cv)
11. [Step 11 — Final Model Training on All Data](#step-11--final-model-training-on-all-data)
12. [Step 12 — Global Feature Importance](#step-12--global-feature-importance)
13. [Step 13 — Per-Surface Feature Importance](#step-13--per-surface-feature-importance)
14. [Step 14 — SHAP Analysis](#step-14--shap-analysis)
15. [Step 15 — SHAP Dependence Analysis](#step-15--shap-dependence-analysis)
16. [Step 16 — SHAP Interaction Analysis](#step-16--shap-interaction-analysis)
17. [Step 17 — Best vs Worst Catalyst Analysis](#step-17--best-vs-worst-catalyst-analysis)
18. [Step 18 — Host-Dopant Interaction Index (HDII)](#step-18--host-dopant-interaction-index-hdii)
19. [Step 19 — Uncertainty Quantification](#step-19--uncertainty-quantification)
20. [Step 20 — Virtual Screening](#step-20--virtual-screening)
    - [Step 20b — Same-Element Filter for Candidates](#step-20b--same-element-filter-for-candidates)
21. [Step 21 — Catalyst Design Map](#step-21--catalyst-design-map)
22. [Step 22 — Quantitative Design Rules](#step-22--quantitative-design-rules)
23. [Step 23 — Master Comparison Table](#step-23--master-comparison-table)
24. [Step 24 — Descriptor Group Ablation](#step-24--descriptor-group-ablation)
25. [Step 25 — Leave-One-Dopant-Out CV — LODO](#step-25--leave-one-dopant-out-cv--lodo)
26. [Step 26 — Leave-One-Chemical-Family-Out Validation](#step-26--leave-one-chemical-family-out-validation)
27. [Step 27 — Physics Baselines + BEP Delta-ML](#step-27--physics-baselines--bep-delta-ml)
28. [Step 28 — Permutation Importance + Consensus Descriptor Ranking](#step-28--permutation-importance--consensus-descriptor-ranking)
29. [Step 29 — Uncertainty Calibration](#step-29--uncertainty-calibration)
30. [Step 30 — Stability-Aware Catalyst Ranking](#step-30--stability-aware-catalyst-ranking)
31. [Step 31 — Q1-Ready Summary Tables and Figures](#step-31--q1-ready-summary-tables-and-figures)
32. [Step 32 — Active Learning Simulation + DFT Recommendations](#step-32--active-learning-simulation--dft-recommendations)
33. [Step 33 — Physics-Informed Neural Network (PINN) Constrained Loss](#step-33--physics-informed-neural-network-pinn-constrained-loss)

</details>

---

## Workflow Sections

### Step 1 — Environment Setup
Add your content here.

### Step 2 — Checkpoint Helper Functions
Add your content here.

### Step 3 — Load Dataset and Engineer Features
Add your content here.

### Step 4 — Exploratory Data Analysis (EDA)
Add your content here.

### Step 5 — Build Feature Matrix
Add your content here.

#### Step 5b — matminer + CALPHAD Feature Enrichment
Add your content here.

#### Step 5c — Clean Combined Feature Matrix
Add your content here.

#### Step 5d — Activate Combined Feature Matrix
Add your content here.

### Step 6 — Define All Models
Add your content here.

### Step 7 — Metric Helper Functions
Add your content here.

### Step 8 — Five-Fold Cross-Validation (RF, DF, MLP)
Add your content here.

#### Step 8b — XGBoost Baseline (5-Fold CV)
Add your content here.

#### Step 8c — Statistical Significance Tests + Confidence Intervals
Add your content here.

### Step 9 — Leave-One-Host-Out CV — LOHO (RF, DF, MLP)
Add your content here.

#### Step 9b — XGBoost LOHO-CV
Add your content here.

### Step 10 — Leave-One-Surface-Out CV — LOSO (RF, DF, MLP)
Add your content here.

#### Step 10b — XGBoost LOSO-CV
Add your content here.

### Step 11 — Final Model Training on All Data
Add your content here.

### Step 12 — Global Feature Importance
Add your content here.

### Step 13 — Per-Surface Feature Importance
Add your content here.

### Step 14 — SHAP Analysis
Add your content here.

### Step 15 — SHAP Dependence Analysis
Add your content here.

### Step 16 — SHAP Interaction Analysis
Add your content here.

### Step 17 — Best vs Worst Catalyst Analysis
Add your content here.

### Step 18 — Host-Dopant Interaction Index (HDII)
Add your content here.

### Step 19 — Uncertainty Quantification
Add your content here.

### Step 20 — Virtual Screening
Add your content here.

#### Step 20b — Same-Element Filter for Candidates
Add your content here.

### Step 21 — Catalyst Design Map
Add your content here.

### Step 22 — Quantitative Design Rules
Add your content here.

### Step 23 — Master Comparison Table
Add your content here.

### Step 24 — Descriptor Group Ablation
Add your content here.

### Step 25 — Leave-One-Dopant-Out CV — LODO
Add your content here.

### Step 26 — Leave-One-Chemical-Family-Out Validation
Add your content here.

### Step 27 — Physics Baselines + BEP Delta-ML
Add your content here.

### Step 28 — Permutation Importance + Consensus Descriptor Ranking
Add your content here.

### Step 29 — Uncertainty Calibration
Add your content here.

### Step 30 — Stability-Aware Catalyst Ranking
Add your content here.

### Step 31 — Q1-Ready Summary Tables and Figures
Add your content here.

### Step 32 — Active Learning Simulation + DFT Recommendations
Add your content here.

### Step 33 — Physics-Informed Neural Network (PINN) Constrained Loss
Add your content here.

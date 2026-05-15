[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20200827.svg)](https://doi.org/10.5281/zenodo.20200827)

Archived and published via Zenodo.

# USCF-UQ

Unified Structural Counterfactual Framework for Domain-General Reasoning Under Uncertainty

---

## Overview

Modern causal reasoning systems often treat causal discovery, effect estimation, counterfactual analysis, and uncertainty quantification as isolated processes. This fragmentation limits interpretability, scalability, and domain generalization across heterogeneous datasets.

USCF-UQ presents a unified structural counterfactual framework designed for domain-general reasoning under uncertainty by integrating:

- Data Understanding
- Structural Causal Graph Construction
- Causal Effect Estimation
- Counterfactual Reasoning
- Uncertainty Quantification
- Generalization and Evaluation

The framework combines causal inference techniques, structural modeling, bootstrap-based uncertainty analysis, and counterfactual simulation into a multi-phase pipeline capable of supporting interpretable reasoning across multiple datasets and domains.

---

## Key Features

- Multi-phase causal reasoning pipeline
- Structural causal DAG generation
- Causal effect estimation using causal inference techniques
- Counterfactual outcome simulation
- Bootstrap-based uncertainty quantification
- Refutation-based causal validation
- Domain-general dataset evaluation
- Interpretable structural reasoning workflow

---

## Technologies Used

| Category | Technologies / Methods Used |
|---|---|
| Programming Language | Python |
| Structural Causal Modeling | DoWhy |
| Machine Learning | Scikit-learn |
| Regression Model | RandomForestRegressor |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Notebook Environment | Jupyter Notebook |
| Serialization | Pickle |
| Dataset Handling | CSV-based Structured Datasets |
| Experimental Methodology | Bootstrap Analysis, Refutation Testing, Counterfactual Simulation |

---

## System Workflow

Data Understanding → Causal DAG Construction → Causal Estimation → Counterfactual Reasoning → Uncertainty Quantification → Generalization → Evaluation

---

## Framework Architecture

The USCF-UQ framework consists of the following phases:

1. Data Understanding and Schema Analysis
2. Structural Causal DAG Generation
3. Causal Effect Estimation
4. Counterfactual Reasoning Engine
5. Uncertainty Quantification
6. Domain Generalization
7. Evaluation and Validation

---

## Datasets

The framework supports heterogeneous structured datasets for evaluating causal reasoning and counterfactual inference across multiple domains.

### Datasets Used

- Diabetes Dataset
- Student Performance Dataset
- Hillstrom E-Mail Marketing Dataset

These datasets were used to evaluate:
- causal structure consistency
- treatment-effect estimation
- counterfactual reasoning behavior
- uncertainty robustness
- domain generalization capability

---

## Methodology

The framework follows a structured causal reasoning pipeline:

### Phase 1 — Data Understanding

- Dataset schema extraction
- Variable inspection
- Feature relationship analysis

### Phase 2 — Causal DAG Generation

- Structural causal graph construction
- Directed acyclic graph representation
- Variable dependency modeling

### Phase 3 — Causal Estimation

- Treatment effect estimation
- Structural causal modeling
- Refutation-based validation

### Phase 4 — Counterfactual Engine

- Counterfactual outcome simulation
- Individual effect analysis
- Average treatment effect computation

### Phase 5 — Uncertainty Quantification

- Bootstrap effect estimation
- Statistical uncertainty analysis
- Robustness evaluation

### Phase 6 — Generalization

- Cross-domain reasoning evaluation
- Multi-dataset consistency analysis

### Phase 7 — Evaluation

- Refutation result analysis
- Bootstrap comparison analysis
- Structural reasoning validation

---

## Experimental Outputs

The framework generates:

- Structural causal artifacts
- Counterfactual effect estimations
- Bootstrap uncertainty summaries
- Refutation analysis results
- Cross-domain generalization outputs
- Evaluation visualizations

---

## Applications

- Causal Inference Research
- Counterfactual Reasoning Systems
- Explainable Artificial Intelligence (XAI)
- Decision Support Systems
- Scientific Machine Learning
- Risk and Uncertainty Analysis
- Domain-General AI Research

---

## Limitations

- Reliance on structured tabular datasets
- Manual assumptions in causal structure modeling
- Limited real-world intervention validation
- Sensitivity to dataset-specific causal assumptions

---

## Future Enhancements

- Automated causal discovery integration
- Probabilistic graphical modeling
- Real-world intervention simulation
- Temporal causal reasoning
- Large-scale domain adaptation
- Advanced uncertainty-aware reasoning systems

---

## Repository Structure

```text
USCF-UQ/
│
├── artifacts/
│   ├── phase1_data_understanding/
│   │   └── data_schema.pkl
│   │
│   ├── phase2_dag_generation/
│   │   └── causal_dag.pkl
│   │
│   ├── phase3_causal_estimation/
│   │   ├── causal_effect.pkl
│   │   └── causal_model.pkl
│   │
│   ├── phase4_counterfactual_engine/
│   │   ├── average_effect.pkl
│   │   ├── counterfactual_model.pkl
│   │   └── individual_effects.pkl
│   │
│   └── phase5_uncertainty_quantification/
│       ├── bootstrap_effects.pkl
│       ├── bootstrap_summary.pkl
│       └── refutation_results.pkl
│
├── data/
│   └── raw/
│       ├── diabetes.csv
│       ├── student-mat.csv
│       └── Kevin_Hillstrom_MineThatData_E-MailAnalytics_DataMiningChallenge_2008.03.20.csv
│
├── notebooks/
│   ├── phase1_data_understanding.ipynb
│   ├── phase2_dag_builder.ipynb
│   ├── phase3_causal_estimation.ipynb
│   ├── phase4_counterfactual_engine.ipynb
│   ├── phase5_uncertainity_quantification.ipynb
│   ├── phase6_generalization.ipynb
│   └── phase7_evaluation.ipynb
│
├── paper/
│   ├── Causal_Counterfactual_Analysis_Framework.pdf
│   └── Causal_Counterfactual_Analysis_Framework.zip
│
├── results/
│   └── phase6_generalization/
│       ├── generalization_results.csv
│       ├── bootstrap_std.png
│       ├── ate_vs_bootstrap_mean.png
│       └── refutation_results.png
│
├── requirements.txt
├── README.md
└── LICENSE

---

## Installation

```bash
git clone <repository-link>
cd USCF-UQ
pip install -r requirements.txt
```

---

## Running the Project

Execute the notebooks phase-by-phase using Jupyter Notebook:

```bash
jupyter notebook
```
Run notebooks sequentially from:

1. phase1_data_understanding.ipynb
2. phase2_dag_builder.ipynb
3. phase3_causal_estimation.ipynb
4. phase4_counterfactual_engine.ipynb
5. phase5_uncertainity_quantification.ipynb
6. phase6_generalization.ipynb
7. phase7_evaluation.ipynb

## Research Contribution

This project proposes a unified structural counterfactual framework capable of integrating causal graph construction, counterfactual reasoning, uncertainty quantification, and domain-general evaluation into a single interpretable reasoning pipeline for artificial intelligence research.

## Author

Yenni Vineeth Kumar
Department of Computer Science and Engineering
Krishna University College of Engineering and Technology
Machilipatnam, Andhra Pradesh, India

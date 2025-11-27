# Federated Learning for GLP-1 Simulated Clinical Trials

## Overview

This README summarizes the UCSF Ideathon Nov 2025 project proposal (**PolyMetrix Health**).

📄 **[Full proposal document](https://docs.google.com/document/d/1lz2C6WVteETNqes0bKrquDn-iVSLxOyCGN7E9AiRMxg/edit?usp=sharing)**

🔧 **[Technical details](https://github.com/Broccolito/PolyMetrixHealth/blob/main/Technical-Details.pdf)**

The project introduces a federated learning platform designed to conduct simulated clinical trials for GLP-1 receptor agonists (e.g., Ozempic). The goal is to enable large-scale, privacy-preserving research across diverse healthcare institutions without centralizing raw patient data.

## Background

GLP-1 receptor agonists have become widely used for weight loss and metabolic conditions. Their diverse physiological impacts present opportunities for drug repurposing, risk stratification, and discovery of broader therapeutic benefits. The availability of large real-world datasets motivates a unified, privacy-conscious analytical framework.

## Innovation

The proposed system uses **federated learning** to connect hospitals, clinics, research institutions, and diagnostic agencies. Participating sites retain patient-level EHR data locally while sharing only: 

- Model weights

- Uncertainty metrics
- Aggregated metadata

This allows collaborative clinical research while ensuring privacy, legal compliance, and institutional autonomy.

## Key Objectives

### 1. Drug Repurposing

Identify novel therapeutic effects of GLP-1 compounds using simulated trial methods (e.g., liver disease progression, cardiovascular events, psychiatric outcomes).

### 2. Patient Stratification

Create risk scores and precision medicine models to determine: 

- Who benefits most

- Optimal dosing strategies
- High-risk subpopulations

### 3. Comparative Efficacy

Evaluate differences between multiple GLP-1 agents using cross-institutional federated simulation.

## Market Positioning

The platform's flexibility and ability to include both high-tech and low-resource institutions appeal to: 

- Pharmaceutical companies (e.g., Eli Lilly) 
- Government agencies (e.g., NIH) 
- Medical societies (e.g., ADA) 

This enables broad collaboration opportunities and a path toward building the largest GLP-1-focused federated research network.

## Go-To-Market Strategy

1.  Begin partnerships with early adopters such as UCSF.\
2.  Expand to additional hospitals and more resource-limited health systems.
3.  Use on-site computation (propensity scores, outcome prediction) to keep raw data local.
4.  Aggregate only de-identified model outputs into the central federated warehouse.

## Conclusion

The PolyMetrix Health federated platform offers: 

- A privacy-preserving architecture

- Leverage of rapidly growing GLP-1 real-world datasets
- Scalability across heterogeneous healthcare institutions
- Modern ML + causal inference methodology

Together, these elements create the most comprehensive GLP-1 simulated clinical trial environment, supporting drug repurposing, personalized medicine, and population-level insights.

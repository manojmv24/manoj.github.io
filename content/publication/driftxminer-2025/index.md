---
title: "DriftXMiner: A Resilient Process Intelligence Approach for Safe and Transparent Detection of Incremental Concept Drift in Process Mining"
authors:
- Puneetha B. H.
- Manoj Kumar M V
- Prashanth B. S.
- Piyush Kumar Pareek
date: "2026-01-01"
publication_types: ["article-journal"]
publication: "*Computers, Materials & Continua*, 86(1), 1-33"
publication_short: "CMC"
doi: "10.32604/cmc.2025.067706"

abstract: "Processes supported by process-aware information systems are subject to continuous and often subtle changes due to evolving operational, organizational, or regulatory factors. These changes, referred to as incremental concept drift, gradually alter the behavior or structure of processes, making their detection and localization a challenging task. Traditional process mining techniques frequently assume process stationarity and are limited in their ability to detect such drift, particularly from a control-flow perspective. We propose DriftXMiner, a control-flow-aware hybrid framework that combines statistical, machine learning, and process model analysis techniques. The approach comprises three key components: (1) Cumulative Drift Scanner that tracks directional statistical deviations to detect early drift signals; (2) a Temporal Clustering and Drift-Aware Forest Ensemble (DAFE) to capture distributional and classification-level changes in process behavior; and (3) Petri net-based process model reconstruction, which enables the precise localization of structural drift using transition deviation metrics and replay fitness scores. DriftXMiner achieves a detection accuracy of 92.5%, a localization precision of 90.3%, and an F1-score of 0.91, outperforming competitive baselines such as CUSUM + Histograms and ADWIN + Alpha Miner."

summary: "Resilient process intelligence framework for detecting incremental concept drift in process mining with 92.5% accuracy"

tags:
- Process Mining
- Concept Drift
- AI Safety
- Safe AI
- Process Intelligence
- Machine Learning
- Petri Nets

featured: true

links:
  - type: source
    name: Publisher
    url: http://www.techscience.com/cmc/v86n1/64402
  - type: source
    name: DOI
    url: https://doi.org/10.32604/cmc.2025.067706

# Publication metadata
publication_info:
  journal: "Computers, Materials & Continua"
  volume: "86"
  issue: "1"
  pages: "1-33"
  year: "2026"
  issn: "1546-2226"
  doi: "10.32604/cmc.2025.067706"

# Special issue
special_issue: "Safe and Secure Artificial Intelligence"
---

**Journal:** Computers, Materials & Continua  
**Volume:** 86, Issue 1  
**Pages:** 1-33  
**Year:** 2026  
**ISSN:** 1546-2226  
**DOI:** [10.32604/cmc.2025.067706](https://doi.org/10.32604/cmc.2025.067706)  
**Publisher Link:** [http://www.techscience.com/cmc/v86n1/64402](http://www.techscience.com/cmc/v86n1/64402)

## Abstract

Processes supported by process-aware information systems are subject to continuous and often subtle changes due to evolving operational, organizational, or regulatory factors. These changes, referred to as incremental concept drift, gradually alter the behavior or structure of processes, making their detection and localization a challenging task. Traditional process mining techniques frequently assume process stationarity and are limited in their ability to detect such drift, particularly from a control-flow perspective. 

The objective of this research is to develop an interpretable and robust framework capable of detecting and localizing incremental concept drift in event logs, with a specific emphasis on the structural evolution of control-flow semantics in processes. 

We propose **DriftXMiner**, a control-flow-aware hybrid framework that combines statistical, machine learning, and process model analysis techniques. The approach comprises three key components:

1. **Cumulative Drift Scanner** that tracks directional statistical deviations to detect early drift signals
2. **Temporal Clustering and Drift-Aware Forest Ensemble (DAFE)** to capture distributional and classification-level changes in process behavior
3. **Petri net-based process model reconstruction**, which enables the precise localization of structural drift using transition deviation metrics and replay fitness scores

## Results

Experimental validation on the BPI Challenge 2017 event log demonstrates that DriftXMiner effectively identifies and localizes gradual and incremental process drift over time:

- **Detection Accuracy:** 92.5%
- **Localization Precision:** 90.3%
- **F1-Score:** 0.91

These results outperform competitive baselines such as CUSUM + Histograms and ADWIN + Alpha Miner. Visual analyses further confirm that identified drift points align with transitions in control-flow models and behavioral cluster structures.

## Contribution

DriftXMiner offers a novel and interpretable solution for incremental concept drift detection and localization in dynamic, process-aware systems. By integrating statistical signal accumulation, temporal behavior profiling, and structural process mining, the framework enables fine-grained drift explanation and supports adaptive process intelligence in evolving environments. Its modular architecture supports extension to streaming data and real-time monitoring contexts.



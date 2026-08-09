# F-PIR: Fuzzy Pivoted Iterative Refinement

This repository contains the source code, experimental data, and  generated tables accompanying the manuscript on **Fuzzy Pivoted Iterative Refinement (F-PIR)** for fuzzy coalition enumeration in UAV pursuit-evasion scenarios.

## Overview

F-PIR is an explicit-state iterative refinement framework for enumerating maximal coalitions in fuzzy UAV coordination graphs.

The implementation includes:

- Construction of fuzzy UAV assignment graphs.
- $\alpha$-cut graph generation.
- Deterministic F-PIR configuration refinement.
- Explicit configuration states $\Gamma=(R,P,X)$.
- Pivot selection based on candidate degree and fuzzy edge weight.
- Configuration-frontier tracking.
- Enumeration of maximal coalitions.
- Deterministic step-by-step execution traces.
- Illustrative configuration reachability examples.
- Experimental evaluation over UAV swarm sizes from 10 to 100.
- $\alpha$-sensitivity experiments.
- Statistical summaries over 200 independent Monte Carlo missions.
- Generation of publication-ready figures and tables.

## Google Colab

The complete experimental implementation is available as a Google Colab notebook:

**[Open the F-PIR Google Colab Notebook](https://colab.research.google.com/drive/1wYimKDFXdhUQ6zyaaBIjKW821q1nFUb2?usp=sharing)**

The notebook can be executed directly in Google Colab without requiring a local Python installation.

## Repository Contents

```text
F-PIR/
│
├── README.md
│
├── code/
│   ├── fpir.py
│   ├── fuzzy_graph.py
│   ├── mission_generator.py
│   ├── experiments.py
│   ├── visualization.py
│   └── illustrative_example.py
│
├── data/
│   ├── experimental_results.csv
│   ├── alpha_sensitivity.csv
│   └── descriptive_statistics.csv
│
├── figures/
│   ├── Figure_1_Execution_Time.pdf
│   ├── Figure_2_Coalitions.pdf
│   ├── Figure_3_Largest_Coalition.pdf
│   ├── Figure_4_Configurations.pdf
│   ├── Figure_5_Frontier.pdf
│   ├── Figure_6_Alpha.pdf
│   ├── Figure_7_Boxplot.pdf
│   └── 3dexample.png
│
└── examples/
    └── f-pir-illustrative-example/

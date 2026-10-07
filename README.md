# Energy Saving Operations of 5G and 6G Networks Using AI

MSc thesis by Praneshraj Tiruppur Nagarajan Dhyaneswar  
Budapest University of Technology and Economics, 2026  
Supervisors: Dr. Tibor Cinkler , Dr.Abdulhalim Fayad

## Overview

This repository contains the completed MSc thesis and original research notebooks for energy-efficient base-station activation in a simulated four-tier heterogeneous network (HetNet).

The work investigates macro, micro, pico and femto base-station activation under changing traffic conditions. It formulates the activation decision as a capacitated, power-weighted set-cover problem and evaluates learning-based approaches against an Integer Linear Programming (ILP) benchmark.

## Contents

- `Thesis_Energy_Saving_5G_6G_using_AI.pdf`  
  Full MSc thesis, including methodology, experiments, results, limitations, and references.

- `AOMTO9_Thesis_Graph_SCP_Semi_Supervised_0706.ipynb`  
  Main Graph-SCP notebook containing the HetNet simulator, ILP benchmark, Topology-Resource Utility Score (TRUS), GraphSAGE model, semi-supervised training, evaluation, and ablation analysis.

- `AOMTO9_Thesis_Reinforcement_Learning_V7.ipynb`  
  Exploratory PPO reinforcement-learning notebook with user mobility and handover analysis.

## Recommended reading order

1. Read the full thesis PDF for methodology, experimental context, results and limitations.
2. Open the Graph-SCP semi-supervised notebook.
3. Open the reinforcement-learning and handover-analysis notebook.

## Important execution note

This repository is an archive of completed MSc thesis research, not a packaged production application.

The Graph-SCP notebook references locally generated training datasets and saved model artifacts that are not included in this repository. Therefore, it is not intended to be executed unchanged from a fresh clone.

The notebooks are provided to document the simulation, modelling, training, evaluation, and analysis used in the thesis.

## Scope

- Four-tier 5G/6G HetNet simulation
- Energy-aware base-station activation
- Capacitated, power-weighted set cover formulation
- Integer Linear Programming benchmark
- Semi-supervised GraphSAGE / Graph-SCP
- Topology-Resource Utility Score (TRUS)
- Exploratory PPO reinforcement learning
- User mobility and handover analysis

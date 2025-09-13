# Online Sparsification of Bipartite-Like Clusters in Graphs

This repository contains code for the paper **"Online Sparsification of Bipartite-Like Clusters in Graphs"**, published in **ICML 2025**.

---

## Installation

To install the necessary dependencies, run:

```bash
pip install -r requirements.txt
```
---
## Reproducing Experiments

**Stochastic Block Models (SBM):** 

To reproduce the experiments on directed and undirected SBMs, execute the following commands:

```bash
python directed.py
python undirected.py
```
**Real-World Graphs:**

To reproduce the results on real-world graph datasets, run:

```bash
python Real_World_Directed.py
python Real_World_Undirected.py
```
---
## Online Sparsification

To demonstrate our primary contribution, where input edges are processed in an online setting, execute:

```bash
python Online_Sparsifier.py

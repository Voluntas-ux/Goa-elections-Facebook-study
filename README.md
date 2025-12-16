## Project Title
Facebook Graph API Analysis of Goa Assembly Elections 2022

## Overview
This repository hosts code and documentation for an academic research project that collects and analyzes **publicly available Facebook Page data** related to the Goa Assembly Elections 2022. The study examines political communication patterns using **network-based methods**, extending prior social media election research (e.g., Chakraborty et al.) by validating similar approaches on Facebook data.

The primary data source is the **Facebook Graph API**. The analysis constructs **keyword–page bipartite networks** derived from political party and actor Pages active in Goa during the election period.

## Research Objectives
- Collect public Facebook Page posts relevant to the Goa Assembly Elections 2022
- Construct a networked dataset based on textual co-occurrence and issue salience
- Compare network structures and analytical insights with prior election-focused social media studies
- Enable downstream visualization and statistical analysis (e.g., degree centrality, betweenness, clustering)

## Data Collection
- **Platform:** Facebook (public Pages only)
- **Method:** Facebook Graph API
- **Time window:** January 1, 2022 – March 15, 2022
- **Fields collected:** Page name, post text, timestamp, permalink

No personal profiles, private accounts, or non-public data are accessed at any stage.

## Repository Structure
- `notebooks/` – Jupyter notebooks for data collection and network construction
- `data/` – CSV outputs of collected Facebook posts
- `docs/` – Privacy Policy and Terms of Service

## Requirements
- Python 3.9+
- requests
- pandas
- networkx

## Ethical and Legal Compliance
This project complies with Facebook Platform Policies. Only publicly accessible Page-level data is collected, no personal user data is stored, and all usage is strictly limited to academic research purposes.

---

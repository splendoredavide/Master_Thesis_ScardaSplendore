# Master_Thesis_ScardaSplendore

This repository contains the code and analysis used to study **factor momentum** and its relationship to **traditional stock momentum** in U.S. equity markets.

The project replicates and extends findings from the recent factor momentum literature, including:

- Ehsani & Linnainmaa (2022)
- Gupta & Kelly (2019)
- Arnott et al. (2019)
- Fan et al. (2022)
- Moskowitz, Ooi & Pedersen (2012)

The analysis is implemented in Python using Jupyter notebooks and focuses on empirical asset pricing, portfolio construction, and momentum-based trading strategies.

---

## Research Objective

The repository investigates whether:

1. Factors exhibit momentum
2. Factor momentum subsumes traditional stock momentum
3. Momentum effects are robust across specifications and factor subsets
4. Factor timing strategies generate abnormal returns

The project builds upon the literature showing that factor returns themselves exhibit autocorrelation and momentum dynamics. Examples include:

- "Factor Momentum Everywhere" by Gupta & Kelly (2019), documenting strong factor momentum across many equity factors
- "Factor Momentum and the Momentum Factor" by Ehsani & Linnainmaa (2019), arguing that stock momentum is largely driven by factor momentum
- "Momentum and Factor Momentum: A Re-examination" (2024), revisiting whether factor momentum fully explains stock momentum

---

## Data

The factor data used in this project comes from the **JKP Factor Library**:

https://jkpfactors.com/

The original dataset is associated with:

> Jensen, Kelly, and Pedersen (2023), *Is There a Replication Crisis in Finance?* :contentReference[oaicite:4]{index=4}

The factors were downloaded from the JKP website and stored locally as:

```text
jkp_factors.csv

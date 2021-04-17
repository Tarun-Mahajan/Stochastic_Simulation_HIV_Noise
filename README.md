# Stochastic simulations for the HIV LTR promoter
This repository contains a Jupyter notebook for recreating Figs. 1C and 1D from
Alex et al. 2021. Both the figures were generated using the R programming language.

The details of the simulations can be found in the methods section of the paper.
Briefly, the two figures perform the following simulations:

1. Fig. 1C--Here, we simulate the two-state promoter model of transcriptional
bursting for the HIV LTR promoter. Simulations were performed for four different
scenarios: 1) untreated (UN); 2) noise enhancer (NE); 3) activator (AC) and 4)
AC + NE. The single-cell time-series simulations show that AC + NE exhibits
synergistic gene expression compared to AC and NE alone.

2. Fig. 1D--This figure shows the noise-vs-mean space plot for different values
of burst size and frequency for the two-state model. Each point in this 2D space
is color-coded according to the % of single-cells which cross the active
replication threshold corresponding to the burst size and frequency for that point.
Burst size and frequency are varied over a grid. Burst size is modulated by changing
the rate of transcription *k*<sub>m</sub>, while burst frequency is modulated by
changing the promoter on rate *k*<sub>on</sub>.

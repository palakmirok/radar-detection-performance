# Radar Detection Performance Analysis

Monte Carlo simulation of a radar detector in Gaussian noise, evaluating
probability of detection (Pd), probability of false alarm (Pfa) and ROC curves.

## What this project does
- Simulates noise-only and signal-plus-noise measurements
- Estimates Pd and Pfa using Monte Carlo trials
- Compares simulation results against theory
- Plots Pd vs signal strength and the ROC curve

## Notebooks
- `PD_vs_Signal_Strength_Graph.ipynb`: Pd as a function of target signal strength (fixed threshold)
- `ROC_Curve.ipynb`: Receiver Operating Characteristic curve

## Key results
- Simulated Pd and Pfa match the theoretical values closely
- Raising the threshold lowers Pfa but also lowers Pd (the Pd-Pfa trade-off)
- Very small Pfa (about 1e-8) needs hundreds of millions of Monte Carlo trials

## Tools
Python, NumPy, SciPy, Matplotlib

## How to run
Open either notebook in Google Colab and click Runtime, then Run all.

## Author
Palak Mirok, ECE, Galgotias University

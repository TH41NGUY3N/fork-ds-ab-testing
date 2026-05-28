# A/B Testing: Frequentist, Bayesian, and Experiment Design Approaches

This project demonstrates statistical A/B testing methodology through a real-world e-commerce dataset. It includes one notebook focused on experiment analysis, one notebook focused on experiment planning, and a guided practice notebook so you can move from interpreting results to designing better tests and then rehearse the full workflow.

## What You'll Learn

- How to properly design and set up an A/B test experiment
- Data cleaning techniques for removing contaminated experimental data
- Frequentist hypothesis testing using chi-square tests and p-values
- Bayesian inference using Beta distributions and posterior probabilities
- Sample-size planning, runtime estimation, and minimum detectable effect (MDE)
- Practice exercises focused on interpretation and decision-making
- How to interpret and communicate statistical results for decision-making

## Notebook Order

Run the notebooks in this order:

1. [01_AB_testing.ipynb](./01_AB_testing.ipynb): Covers data cleaning, exploratory analysis, and post-hoc A/B test evaluation using frequentist and Bayesian approaches.
2. [02_AB_testing_experiment_design.ipynb](./02_AB_testing_experiment_design.ipynb): Builds on the same dataset to estimate baseline conversion, required sample size, expected runtime, and realistic detectable lift for future tests.
3. [03_AB_testing_practice_lab.ipynb](./03_AB_testing_practice_lab.ipynb): Reinforces the first two notebooks with guided exercises, student TODO cells, and solution cells focused on interpretation and business decisions.

## Getting Started

Install the virtual environment and the required packages by following commands:

**macOS type the following commands:**

```pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

**Windows** type the following commands :

**For PowerShell CLI:**

```pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install -r requirements.txt
```

**For Git-Bash CLI:**

```pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
pip install --upgrade pip
pip install -r requirements.txt
```

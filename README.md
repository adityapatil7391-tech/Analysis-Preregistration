# Analysis Preregistration and Reproducible Research

## Project Overview

This project demonstrates a preregistered and reproducible statistical analysis workflow.

The research question examines whether weekly study hours are associated with students' examination scores.

## Research Question

Does the number of hours students study per week during the four weeks preceding an examination significantly predict examination scores?

## Main Variables

* Study Hours — Primary predictor
* Exam Score — Primary outcome
* Attendance — Control variable
* Previous Score — Control variable

## Repository Structure

```text
analysis-preregistration/
├── README.md
├── preregistration.md
├── requirements.txt
├── environment.yml
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
├── notebooks/
│   └── 01_analysis.ipynb
├── src/
│   ├── data_processing.py
│   ├── analysis.py
│   └── validation.py
├── tests/
│   └── test_pipeline.py
└── reports/
    └── analysis_report.md
```

## Reproducibility

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Run the synthetic pipeline test:

```bash
pytest
```

## Statistical Analysis

The planned analysis includes:

* Descriptive statistics
* Pearson correlation
* Linear regression
* Effect sizes
* 95% confidence intervals
* Assumption checks
* Robustness analysis using Spearman correlation when appropriate

## Data-Blind Validation

Before examining the real outcome relationships, the processing pipeline is tested using synthetic data.

The synthetic test validates data structure, exclusion rules, missing-data handling, and expected output contracts.

## Expected Proof

The completed repository contains:

1. Preregistration document
2. Reproducible environment files
3. Raw, interim, and processed data directories
4. Analysis notebook
5. Analysis/report files
6. Synthetic pipeline test
7. Documented expected output contracts

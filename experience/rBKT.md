# rBKT Project Experience Report

## Background

Organization: Feng Ji Lab, University of Toronto

Project: [BKT: Bayesian Knowledge Tracing in R](https://github.com/Feng-Ji-Lab/BKT)

Position: Research Developer

Project Period: August 2024 – December 2025

Project Type: Open-source educational data mining research

## Publication

Yuan, Y., Zhou, B., Qi, J., Luo, N., & Ji, F. (2026). BKT: A Bayesian knowledge tracing package for the R environment. *Behavior Research Methods, 58*(5), Article 134. [https://doi.org/10.3758/s13428-026-02955-9](https://doi.org/10.3758/s13428-026-02955-9)

## Main Responsibilities and Results

Contributed to the development of an R implementation of Bayesian Knowledge Tracing and its variants.

* Helped translate the model workflow and developer-facing APIs into an R package for estimating student knowledge mastery from problem-solving sequences.

Improved the model training and prediction workflow.

* Developed and refined prediction functions, parameter handling, input validation, and data-conversion utilities.

Supported model evaluation and simulation.

* Added simulation data generation and model-evaluation utilities, including mean squared error analysis and parameter-recovery experiments.

Improved package usability and reliability.

* Added missing-data checks, fixed default-parameter behavior, updated examples and documentation, and supported package rebuilds and version updates.

## Reflection & Learning

This project strengthened my understanding of how statistical models can be transformed into accessible research software. A correct implementation is only one part of a useful package: researchers also need clear APIs, reliable input validation, reproducible experiments, and documentation that connects mathematical concepts with practical workflows.

Working on rBKT also deepened my interest in educational data mining. Bayesian Knowledge Tracing provides an interpretable way to estimate how student knowledge changes over time, while simulation and parameter-recovery experiments help reveal when model estimates can be trusted. The experience showed me the value of combining software engineering practices with educational research methodology.

## Detailed Projects

### Model Training and Prediction

Key words: **R, Bayesian Knowledge Tracing, statistical modeling, prediction**

* Contributed to APIs for fitting BKT models and producing student performance and knowledge-state predictions.
* Improved parameter defaults and validation to make model behavior more consistent across training and prediction workflows.
* Supported common educational datasets while allowing users to provide custom column mappings for other data sources.

### Simulation and Evaluation

Key words: **simulation, MSE, parameter recovery, reproducibility**

* Developed utilities for generating simulated student-response sequences.
* Added evaluation support for comparing estimated results with observed or simulated outcomes.
* Used parameter-recovery experiments to examine whether the implementation could recover known model parameters from generated data.

### Package Quality and Documentation

Key words: **R package development, testing, validation, documentation**

* Added checks for missing or invalid data and resolved issues involving fit and prediction parameters.
* Updated tutorials, examples, and research documentation to make the package easier to understand and use.
* Supported package version updates and rebuilds as the implementation evolved.

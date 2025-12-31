# COPD Prediction Using PPG Signals Dataset

This repository provides the datasets supporting the study:

“Ultra-Short PPG-Based Screening of COPD Using Ensemble Machine Learning Models.”

The dataset was collected as part of a clinical screening study aimed at evaluating the feasibility of photoplethysmography (PPG) signals for non-invasive Chronic Obstructive Pulmonary Disease (COPD) detection using machine learning techniques.

All data are derived from clinically screened participants and organized to facilitate reproducible experimentation with varying signal durations.

Dataset Description

The dataset consists of PPG signal segments extracted at multiple time resolutions to investigate the effect of signal length on COPD classification performance.

The total number of participants in this study is six (6), reflecting a controlled pilot-scale clinical screening setting. Despite the limited cohort size, the dataset is structured to enable methodological evaluation, feature analysis, and model benchmarking.
Dataset Contents

The repository is organized into the following directories, each corresponding to a different PPG segment duration:

2s_db/
PPG signal segments of 2-second duration

16s_db/
PPG signal segments of 16-second duration

32s_db/
PPG signal segments of 32-second duration

64s_db/
PPG signal segments of 64-second duration

128s_db/
PPG signal segments of 128-second duration

256s_db/
PPG signal segments of 256-second duration

Each directory contains preprocessed PPG data suitable for direct use in machine learning pipelines, including feature extraction, classification, and performance comparison across temporal resolutions.

Key Features

Multi-Resolution Analysis
Enables systematic evaluation of COPD detection performance across ultra-short to longer PPG signal windows.

Clinically Screened Data
All recordings originate from a controlled clinical screening process, ensuring medical relevance.

Privacy-Preserving Format
Data are provided as signal segments only; no personally identifiable information is included.

Machine Learning Ready
Structured to support classical and ensemble-based ML models without additional preprocessing requirements.

Intended Use

This dataset is intended for:

Research on non-invasive respiratory disease screening

Studies exploring PPG-based physiological signal analysis

Benchmarking machine learning models for small-sample clinical datasets

Feasibility and pilot studies for wearable health monitoring systems

The dataset is not intended for direct clinical diagnosis or standalone medical decision-making.

Limitations

The dataset includes a limited number of participants (n = 6) and should be considered exploratory.

Results derived from this data should be interpreted as methodological validation, not population-level inference.

License

This dataset is provided for research and educational purposes only.

Any use of this data must appropriately cite the associated publication.

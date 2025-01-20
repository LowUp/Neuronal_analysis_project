# Computational Models of Neuronal Constellation

## Overview

This repository contains the research and implementation of computational models for analyzing neuronal activity and decoding behavioral categories from neural spike trains. The project focuses on using Leaky Integrate-and-Fire (LIF) models and machine learning techniques to process and interpret neuronal data.

## Contents

The PDF [NEURONAL ANALYSIS ASSESSMENT](./NEURONAL_ANALYSIS_ASSESSMENT.pdf) file in this repository covers the following topics:

1. **Abstract**: Brief overview of the research, methods, and key findings.

2. **Methodology**:
   - Implementation using Python and libraries (NumPy, pandas, scikit-learn)
   - Spiking Models: Leaky Integrate-and-Fire (LIF) model and its extended version
   - Firing Rate calculation methods

3. **Artificial Spike Train Generation**:
   - Network of interconnected LIF models
   - Simulation results and comparison with real data
   - Similarity evaluation using Inter-Spike Interval (ISI) and Spike count error

4. **Optimal Firing Rate Estimation**:
   - Sliding window strategy
   - Correlation analysis
   - Visual comparison of real and artificial firing rates

5. **Decoding Behavioral Categories**:
   - Implementation of six classification models
   - Feature preparation and training methodology
   - Results comparison between real and artificial data

6. **Discussion**: Analysis of results and potential improvements for each section

## Key Features

- Generation of artificial spike trains using LIF models
- Comparison of artificial and real neuronal activity
- Optimal firing rate estimation techniques
- Machine learning classifiers for decoding behavioral categories
- Comprehensive performance analysis and visualizations

## Getting Started

To use the code and reproduce the results:
1. ```bash
   git clone https://github.com/LowUp/Neuronal_analysis_project.git
   ```
2. ```bash
   pip install -r requirements.txt
   ``` 
3. Run the provided Python scripts to execute the analyses (Use `Jupyter Notebook` for a better visual experience)

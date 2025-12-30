# Alzheimer’s Language Feature Analysis

## Overview
This project analyzes language patterns in speech transcripts from healthy individuals and patients with Alzheimer’s disease. The goal is to quantify interpretable linguistic features and examine how they differ between groups.

This project is intended for research and educational purposes only and is not a diagnostic tool.

## Motivation
Language degradation is a well-documented early indicator of Alzheimer’s disease. By measuring simple and interpretable linguistic features such as vocabulary diversity and repetition, this project aims to support research into non-invasive cognitive screening methods.

## Methods
We extract and analyze the following features from text transcripts:
- Word count
- Vocabulary diversity (unique words divided by total words)
- Repetition score (frequency of the most common word)

Group-level comparisons and visualizations are used to analyze differences between healthy controls and Alzheimer’s patients.

## Results
Initial analysis demonstrates measurable differences in linguistic features between the two groups, particularly in vocabulary diversity and repetition patterns.

## Limitations
- Small sample size
- Text-only analysis
- No clinical diagnosis is performed
- Results depend on dataset quality

## Ethical Considerations
All data used in this project is de-identified and publicly available. This work is intended solely for research and educational purposes.

## Future Work
- Statistical significance testing
- Larger and more diverse datasets
- Longitudinal analysis of language changes
- Integration of additional modalities such as speech timing features

## Reproducibility
All analysis code is contained in `analysis.ipynb`. Required dependencies are listed in `requirements.txt`.

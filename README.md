# Linguistic Feature Analysis for Alzheimer’s Detection

## Problem
Alzheimer’s disease affects language production, often leading to reduced vocabulary
and increased repetition. Early linguistic markers could support non-invasive screening
and research into cognitive decline.

## Dataset
The dataset consists of de-identified text samples labeled as:
- `alzheimer`
- `control`

Each sample represents a speech or language transcription.

## Approach
We extract simple, interpretable linguistic features from each text sample:

- **Word Count** – total number of words
- **Vocabulary Diversity** – ratio of unique words to total words
- **Repetition Score** – proportion of the most repeated word

These features are compared between Alzheimer’s and control groups.

## Methods
- Tokenization using whitespace splitting
- Feature extraction using Python
- Group-wise statistical aggregation
- Visualization using boxplots

## Results
The analysis shows noticeable differences between groups:
- Alzheimer’s samples tend to have lower vocabulary diversity
- Repetition scores are higher compared to controls

This supports existing linguistic findings in Alzheimer’s research.

## Limitations
- Basic lexical features only
- No syntactic or semantic modeling
- Not intended for clinical diagnosis

## Reproducibility
To run the analysis:

```bash
pip install -r requirements.txt
python analysis.py

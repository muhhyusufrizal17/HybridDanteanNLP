# HybridDanteanNLP
Hybrid Dantean NLP prototype for ambiguity-aware emotional state classification using Threshold-based Naive Bayes, Log-Likelihood Ratio, Mamdani Fuzzy Inference, and planned Wang–Mendel rule generation. Current stage: corpus prep, probabilistic modeling, and fuzzy-rule design. The project uses Dantean symbolic structure as an interpretative layer for emotional classification, where textual expressions are mapped into three major emotional states:

- **Inferno**: negative, distress-oriented, or emotionally intense states
- **Purgatorio**: ambiguous, transitional, reflective, or healing-oriented states
- **Paradiso**: regulated, positive, stable, or resolution-oriented states

The framework combines:
- **Threshold-based Naive Bayes**
- **Log-Likelihood Ratio analysis**
- **Dantean symbolic hierarchy**
- **Fuzzy Mamdani inference design**
- **Wang–Mendel rule generation design**
- **Planned expert-rule validation**

At the current stage, the fuzzy expert-rule component is still in the design phase. Therefore, this repository presents the system as a research prototype and methodological framework, not as a clinically validated psychological assessment tool.

---

## Research Background

Emotion classification in social media and literary texts often struggles with ambiguity, symbolic meaning, and transitional emotional states. Many machine learning models classify emotions into fixed labels, but they may fail to represent uncertainty when a text contains mixed, unstable, or context-dependent emotional signals. This project addresses that limitation by introducing a Dantean interpretative hierarchy. Instead of treating emotional states as purely discrete categories, the framework interprets emotional expressions through three symbolic domains:

| Dantean Layer | Emotional Interpretation |
|---|---|
| Inferno | Negative, chaotic, painful, or distress-related emotional states |
| Purgatorio | Ambiguous, transitional, reflective, or unresolved emotional states |
| Paradiso | Positive, regulated, accepting, or emotionally resolved states |

The goal is to build an ambiguity-aware classification system that can identify not only dominant emotional polarity, but also transitional uncertainty between states.

---

## Project Objectives

1. To build a Dantean-inspired emotional classification framework.
2. To classify text into Inferno, Purgatorio, and Paradiso emotional states.
3. To apply Threshold-based Naive Bayes for probabilistic classification.
4. To use Log-Likelihood Ratio for identifying discriminative emotional cues.
5. To design a fuzzy Mamdani inference system for ambiguity handling.
6. To prepare a future expert-rule validation stage for fuzzy rule construction.
7. To compare the proposed approach with conventional NLP baselines.

---

## Current Research Status

This project is currently in the **research design and prototype stage**.

Completed or partially completed components:

- Corpus preparation from *The Divine Comedy*
- Dantean emotional state mapping
- Threshold-based Naive Bayes classification design
- Log-Likelihood Ratio cue extraction
- Purgatorio ambiguity testing concept
- Social media emotion dataset benchmarking concept
- Fuzzy Mamdani inference structure design

Components still under development:

- Expert judgment collection
- Expert-rule validation
- Final Mamdani fuzzy rule base
- Full fuzzy inference evaluation
- Comparative evaluation against transformer-based baselines

Because the expert-rule stage has not yet been completed, the fuzzy component is presented as a **proposed inference design**, not as a finalized validated system.

---

## Methodological Framework

The proposed pipeline consists of the following stages:

```text
Dante Corpus Preparation
        ↓
Text Cleaning and Preprocessing
        ↓
Dantean Emotional Layer Mapping
        ↓
Threshold-based Naive Bayes Classification
        ↓
Log-Likelihood Ratio Cue Extraction
        ↓
Ambiguity Detection
        ↓
Fuzzy Mamdani Inference Design
        ↓
Planned Expert Rule Validation
        ↓
Final Emotional State Classification

---
## Project Workflow

This project is developed as a research prototype for Dantean-inspired emotional state classification. The workflow consists of several experimental stages:

1. **Environment Setup**  
   Install required libraries, mount Google Drive, and define the working directories for raw data, processed data, figures, benchmark datasets, and experimental results.

2. **Dante Corpus Preparation**  
   Load *Inferno*, *Purgatorio*, and *Paradiso* PDF files, extract the text, clean unnecessary headers, footers, footnotes, and split the corpus into canto-level text files.

3. **Text Preprocessing and SNS Normalization**  
   Normalize text using tokenization, lowercasing, slang normalization, word elongation handling, stopword removal, and informal SNS-style cleaning.

4. **Dantean Label Construction**  
   Build a labeled corpus based on the symbolic structure of *The Divine Comedy*. Inferno and Paradiso are used as polarity anchors, while Purgatorio is treated as a transitional or ambiguous emotional zone.

5. **Log-Likelihood Ratio Analysis**  
   Calculate token-level Log-Likelihood Ratio scores to identify lexical cues that distinguish Inferno-oriented and Paradiso-oriented emotional expressions.

6. **Canto-Level Symbolic Scoring**  
   Compute signed LLR scores and emotional intensity scores for each canto to represent the symbolic emotional tendency of each textual segment.

7. **Fuzzy Membership Design**  
   Construct fuzzy membership functions for Dantean emotional interpretation, including Inferno, Purgatorio, and Paradiso membership regions.

8. **Threshold-based Naive Bayes Classification**  
   Train and evaluate a Naive Bayes classifier using Dantean-labeled text. The model is used as the probabilistic classification layer of the framework.

9. **Hybrid Dantean Inference Prototype**  
   Combine probabilistic scores, LLR-based symbolic cues, fuzzy membership values, and contextual emotional cues to produce Dantean emotional state predictions.

10. **SNS Text Testing**  
   Test the model using user-input or social media text. The input text can be normalized, translated if necessary, scored using LLR, and classified into Dantean emotional states.

11. **Contextual Override Layer**  
   Apply rule-based contextual checks for hostility, recovery, uncertainty, emotional masking, exhaustion, and other SNS-specific cues.

12. **Baseline Comparison**  
   Compare the proposed Dantean Hybrid prototype with conventional and modern NLP baselines such as VADER, SVM, DistilBERT, IndoBERT, and XLM-RoBERTa.

13. **SNS Benchmark Dataset Construction**  
   Build a multi-emotion SNS benchmark dataset from categories such as anger, fear, joy, love, neutral, and sadness.

14. **Benchmark Evaluation**  
   Evaluate the framework on SNS benchmark data and compare its performance against baseline models.

15. **Ablation Study**  
   Test the contribution of each component, including TB-NB only, TB-NB + LLR, Dantean hierarchy, fuzzy ambiguity layer, and full hybrid configuration.

16. **Threshold Sensitivity Analysis**  
   Analyze how LLR threshold, fuzzy threshold, and contextual override threshold affect the performance of the hybrid framework.

17. **Adaptive Fuzzy Experiment**  
   Experiment with confidence-based fuzzy activation to reduce over-adjustment and improve ambiguity handling.

18. **Planned Wang–Mendel Rule Generation**  
   The Wang–Mendel rule generation stage is planned as a future extension to generate fuzzy rules from data patterns and reduce dependency on fully manual rule construction.

19. **Planned Expert Rule Validation**  
   Expert judgment is planned for validating Dantean symbolic mapping, fuzzy linguistic variables, Mamdani rule structure, and Wang–Mendel-generated rules.

20. **Final Research Development**  
   The current notebook represents an experimental prototype. Further development will focus on expert validation, rule refinement, reproducibility improvement, and journal/thesis preparation.

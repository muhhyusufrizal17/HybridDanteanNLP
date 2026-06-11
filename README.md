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

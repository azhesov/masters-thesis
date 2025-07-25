# Masters Thesis  
**Prompting Large Language Models for Controlled Readability: Investigating the Ability of LLMs to Generate Readability-Constrained Text**  
**Author:** Andrejs Žestjaņņikovs (2829510)  
**Institution:** Vrije Universiteit Amsterdam  
**Supervisor:** Davide Ceolin  
**Date:** July 15, 2025  

---

## Overview

This thesis explores the use of prompting techniques to control the readability of text generated by Large Language Models. The research addresses two central tasks:

1. **Readability-Constrained Text Generation:**  
   Investigating whether LLMs can generate text at specified readability levels.

2. **Automated Readability Evaluation:**  
   Evaluating how accurately LLMs follow readability constraints by comparing their outputs using readability metrics and semantic similarity measures.

---

## Goal

The main objective is to **develop prompting techniques** that can accurately instruct LLMs to generate content aligned with predefined readability levels while preserving semantic content. The thesis also evaluates how model configuration and prompt structure influence performance across different settings.

---

## Methodology

- **Prompting Techniques:**  
  - Zero-Shot  
  - Few-Shot  
  - Two-Step  
  - Chain-of-Thought  
  - Chain-of-Thought Advanced  

- **Readability Metrics Used:**  
  - Flesch-Kincaid Grade Level  
  - Flesch Reading Ease  
  - Gunning Fog Index  
  - SMOG, ARI, Coleman-Liau, Spache and Linsear Write.

- **Evaluation Metrics:**  
  - Normalized Absolute Distance (for readability targeting)  
  - Cosine Semantic Similarity (for meaning preservation)

- **Statistical Analysis:**  
  - ANOVA, Tukey HSD and visual plots for performance comparison across prompt types and model scales.

---

## Dataset and Setup

- **Topics:** Selected from the MMLU dataset (general knowledge, manually filtered).
- **Few-shot examples:** Extracted from the CLEAR corpus.
- **Models:** Multiple LLMs, including open-source transformers, evaluated across multiple generation conditions.
- **Output lengths:** 50, 100, 150, 200 words.

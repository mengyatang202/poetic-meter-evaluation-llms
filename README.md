# Poetic Meter Evaluation in Large Language Models

This repository contains the data, prompts, model outputs, and evaluation scripts
for my bachelor's thesis:

**"Poetic Meter Evaluation in Large Language Models"**

## Project Overview

The goal of this project is to evaluate the ability of large language models (LLMs)
to identify poetic meter across multiple languages.

Key features:
- Multilingual poetic dataset (English, Chinese, Arabic & Persian)
- Unified JSON schema for poetic meter annotation
- Gold-standard meter labels
- Multiple open-source LLMs and prompt variants
- Multiple-choice evaluation setting (random baseline: 25%)
- Quantitative accuracy evaluation and qualitative error analysis

## Models Evaluated

- LLaMA 3.3 (70B)
- LLaMA 3.1 (70B)
- Gemma 2 (27B)
- Mistral (7B)
- Qwen 2.5 (72B)
- Command R (35B)

## Repository Structure

See the folder structure for:
- `data/`: raw, cleaned, and annotated poetic datasets
- `prompts/`: prompt templates used for evaluation
- `experiments/`: model-specific outputs
- `evaluation/`: accuracy metrics and protocols
- `error_analysis/`: error categorization and LaTeX tables

## Evaluation Setup

Each poem is associated with a gold meter label.
Models are required to select the correct meter from four options,
resulting in a random baseline accuracy of 25%.

## Status

This repository is under active development and reflects an academic research project.


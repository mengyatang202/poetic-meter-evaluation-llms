# Error Analysis

This folder contains the error analysis component of the project, focusing on systematic failure patterns in LLM-based poetic meter recognition.

The analysis is written in LaTeX and was originally developed as part of the Bachelor thesis. It complements the quantitative evaluation by providing qualitative and structural insights into model errors.

---

## Contents

- LaTeX source files for error analysis
- Tables summarizing common error types
- Analytical commentary on observed failure patterns

The tables include categorized errors such as:
- Incorrect meter assignment despite correct syllable segmentation
- Structurally valid but metrically incorrect patterns
- Cross-lingual transfer errors (e.g. applying English stress logic to non-stress-based meters)
- Prompt-induced hallucinations or format violations

---

## Purpose of Error Analysis

The goal of this analysis is not to maximize accuracy scores, but to:
- Identify systematic weaknesses across model families
- Compare error distributions between languages
- Examine how prompt design influences failure modes
- Provide interpretable explanations beyond aggregate metrics

This analysis supports a more nuanced evaluation of LLM capabilities in handling structured poetic forms.

---

## Relation to Other Components

- Quantitative results are reported in `evaluation/accuracy_results/`
- Evaluation criteria are defined in `evaluation/evaluation_protocol.md`
- Prompts used in the experiments are documented in `prompts/`

Together, these components form a complete evaluation pipeline:
prompt design → model output → quantitative metrics → qualitative error analysis.

---

## Notes

- The LaTeX files are intended for documentation and analysis purposes.
- They are not required to reproduce the experiments themselves.
- Readers interested in methodological details should refer to the evaluation protocol.

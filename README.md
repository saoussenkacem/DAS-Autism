# DAS-Autism
### A Rule-Based Expert System for Autism Diagnosis Support Using Multi-Valued Logic

## Overview

**DAS-Autism** is a Java-based rule-based expert system developed to support autism diagnosis through symbolic multi-valued logic and approximate reasoning.

The system was designed as part of doctoral research and aims to assist in the evaluation of autism-related symptoms by representing their intensity through linguistic values and applying a knowledge-based reasoning mechanism.

Unlike conventional machine learning approaches, DAS-Autism relies on an explicit knowledge base and an inference engine, making its reasoning process interpretable and traceable.

## Main Features

- **Knowledge-based reasoning:** Uses a set of diagnostic rules and symptoms to evaluate autism-related characteristics.
- **Multi-valued logic:** Represents symptom intensity using multiple linguistic values.
- **Linguistic modifiers:** Incorporates linguistic modifiers to refine the representation and interpretation of symptom intensity.
- **Approximate reasoning:** Handles imprecise information through a symbolic reasoning mechanism.
- **Explainable results:** Provides diagnostic conclusions together with a trace of the inference process.
- **Graphical user interface:** Offers an interactive Java-based interface for entering symptoms and viewing the system's results.

## Knowledge Base

The knowledge base was constructed using autism-related diagnostic criteria from the DSM-IV-TR and enriched through collaboration with child psychiatrists.

It includes:
- 15 diagnostic symptoms.
- 23 inference rules.
- Linguistic representations of symptom intensity.
- A reasoning mechanism based on multi-valued logic and linguistic modifiers.

## System Architecture

DAS-Autism was developed using **RAMOLI**, a generic Java-based knowledge-based system shell.

The architecture consists of:
1. **User Interface:** Allows users to enter and consult symptom information.
2. **Knowledge Base:** Stores diagnostic symptoms and inference rules.
3. **Inference Engine:** Applies multi-valued logic and approximate reasoning.
4. **Explanation Component:** Provides a trace of the reasoning process and the resulting assessment.

## Experimental Evaluation

The system was evaluated using 40 real cases from the Child Psychiatry Department of Razi Hospital.

The experimental results reported in the original publication include:
- 29 true positives.
- 11 true negatives.
- 0 false positives.
- 0 false negatives.
- 85% exact agreement in severity assessment.

These results are specific to the experimental dataset and evaluation protocol described in the publication. They should not be interpreted as evidence of general clinical validity.

## Technologies

- **Programming language:** Java
- **Approach:** Rule-based expert system
- **Reasoning:** Symbolic multi-valued logic
- **Knowledge representation:** Diagnostic rules and linguistic modifiers
- **Interface:** Java graphical user interface

## Scientific Publication

This software is described in the following scientific publication:

**DAS-Autism: A Rule-Based System to Diagnose Autism Within Multi-valued Logic.**

Published in *Smart Systems for E-Health*, Springer, 2021.

[Insert the official Springer chapter link or DOI here.]

Please cite the original publication when using or referring to this software.

## Intended Use and Disclaimer

DAS-Autism is a research prototype developed for scientific investigation and as a decision-support tool for autism-related assessment.

It is not intended to replace professional clinical evaluation, medical expertise, or a comprehensive diagnostic assessment. Its experimental results do not establish clinical validity for all populations or settings.

## Usage and Copyright

Copyright © 2021–2026 DAS-Autism authors.

The source code is made available for consultation and use under the conditions specified in the accompanying LICENSE file.

Modification, redistribution, and commercial use are not permitted without prior written authorization from the copyright holders.

## Acknowledgments

The authors acknowledge the contribution of the child psychiatry specialists involved in the development and evaluation of the knowledge base.

## Contact

For scientific questions, collaboration, or authorization requests, please contact the corresponding author.

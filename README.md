# Framed Secondary Instructions: Data and Materials

Data and materials for the article:

> Hamidavi, A. *Differential Compliance With Framed Secondary Instructions in Three Frontier Language Models: An Exploratory Comparison.* Submitted to *AI and Society*, November 2026. Preprint: Research Square, rs-10728137. The same materials are also deposited on the Open Science Framework: [osf.io/g9w3e](https://osf.io/g9w3e/).

## About the study

Each elicitation instance gives a model a primary task together with a secondary instruction whose framing varies (45 instances across GPT-5.4, Claude 4.6 Sonnet, and Gemini 3.1 Pro). The study codes whether and how the model complies with the secondary instruction relative to the primary task, and compares the three models' compliance profiles across framings. This repository deposits the complete instance histories, the per-model codebooks, the feature dataset, and the statistical outputs.

## Contents

| Folder | Contents |
| --- | --- |
| `transcripts/` | The complete instance histories for the three models (JSON). Typeset chat-transcript PDFs of the same histories are in the OSF deposit. |
| `codebooks/` | The per-model codebooks (JSON). PDF renderings are in the OSF deposit. |
| `data/` | The final dataset, the extended-conversations table, the standard-tests table, the model summary, and the compiled output file. |
| `results/` | The analysis report (HTML) and the executive summary. |
| `coding-data/` | The inter-rater reliability report (plain-text rendering of the archived PDF). |
| `documentation/` | The readme deposited with the OSF materials. |

The interactive dashboard pages and figure images of the OSF deposit are omitted in this text deposit; every plotted value is present in the data tables.

## Citation

Please cite the article. Citation metadata is provided in [CITATION.cff](CITATION.cff).

## Licences

Data, transcripts, and documentation are released under the Creative Commons Attribution 4.0 International licence (CC BY 4.0, see [LICENSE](LICENSE)). Code is released under the MIT licence (see [LICENSE-CODE](LICENSE-CODE)).

The transcripts are outputs of publicly available AI systems, generated for this study. They contain no personal data.

## Contact

Abbas Hamidavi
Department of Computer Engineering, Mashhad Branch, Islamic Azad University, Mashhad, Iran
ORCID: [0009-0001-7342-7844](https://orcid.org/0009-0001-7342-7844)

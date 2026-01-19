# Indic LLM Safety Evaluation: Marathi Context

## Project Overview
This research project aims to evaluate the "multilingual alignment gap" in Large Language Models (LLMs), specifically focusing on **Marathi**. While modern LLMs exhibit robust safety guardrails in English, there is a hypothesis that these guardrails degrade or behave inconsistently when processing low-resource Indic languages, particularly involving dialect-specific or culturally nuanced queries.

**Current Status:** Research Design & Dataset Preparation Phase.

## Research Objectives
1.  **Quantify Safety Gaps:** Measure the disparity in safety violations between English and Marathi prompts for identical adversarial intents.
2.  **Cultural Red-Teaming:** Identify failure modes where literal translations of safe English concepts become culturally offensive or inappropriate in a regional Marathi context.
3.  **Automated Evaluation:** Develop a pipeline using LangChain/Genkit to automate the testing process.

## Methodology
The project will follow a comparative analysis approach:
* **Dataset:** Curation of a parallel corpus of adversarial prompts (translated and culturally adapted from standard red-teaming datasets).
* **Model:** Testing against standard industry models (Anthropic Claude, etc.) via API.
* **Metric:** Violation Rate (VR) comparison between English and Marathi outputs.

## Tech Stack
* **Language:** Python 3.10+
* **Frameworks:** LangChain, Google Genkit (for evaluation pipelines)
* **Data Handling:** Pandas, NumPy
* **APIs:** Anthropic API (Pending Access)

## Roadmap
- [x] Literature review on Multilingual Safety.
- [ ] Construction of Marathi Red-Teaming Dataset (In Progress).
- [ ] Development of API wrapper for automated testing.
- [ ] Analysis of initial results and safety report generation.

---
*Note: This repository is currently under active development as part of an independent student research initiative.*

# Claude Extensions

This repository contains a notebook that visualizes and explains how a conversational AI workflow can move from an unverified, hallucinated answer to a more controlled and reliable interaction pattern.

## Project purpose

The notebook demonstrates the difference between:

- a standard chat response without evidence checks
- a constrained workflow using a skill or rule-based fallback
- a structured sequence of steps showing how the system decides whether to answer, ask for more context, or refuse to provide unsupported facts

It is designed to be educational and presentation-friendly, especially for technical demonstrations, architecture discussions, and AI reliability reviews.

## Notebook

- `Claude_Extensions_Interaktive_Animation_DE_proportional_80.ipynb`

This notebook includes HTML/CSS-based visual explanations and animated flow diagrams to highlight:

- hallucination risk in chat-driven assistants
- the role of tools and context in answer generation
- the impact of skills and fallback logic
- a structured decision path for evidence-based responses

## Requirements

A Python environment with Jupyter support is required.

```bash
python -m venv .venv
.venv\Scripts\python -m pip install --upgrade pip
.venv\Scripts\python -m pip install jupyter ipykernel ipython
```

## Run locally

From the project root:

```bash
.venv\Scripts\python -m jupyter notebook
```

Then open the notebook in the browser and select the kernel for this environment.

## Repository contents

- `Claude_Extensions_Interaktive_Animation_DE_proportional_80.ipynb` — the main interactive notebook
- `requirements.txt` — installed Python dependencies
- `.venv/` — local virtual environment (not usually committed in shared repositories)
- `.vscode/settings.json` — workspace Python interpreter configuration

## Notes

This project is primarily a visual explanation and demonstration asset rather than a production data science pipeline. Its main goal is to communicate the reliability principles behind AI-assisted workflows in a clear and engaging way.

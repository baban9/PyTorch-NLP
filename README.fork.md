# PyTorch-NLP (Fork)

> **Fork of [PetrochukM/PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP).** Active development happens upstream. This clone is for reference and local experimentation.

## What it is

`torchnlp` is a PyTorch library for NLP: datasets, embeddings, metrics, and training utilities with tests and documentation.

## Why it is in this portfolio

Included as a reference implementation of a well-structured ML library (packaging, tests, CI, docs). Not presented as original authorship.

## Reproducibility

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pip install -e .
pytest tests/
```

## Sync policy

- Track upstream releases periodically
- Do not modify fork without documenting divergence from upstream
- Prefer contributing fixes upstream when possible

## Tech stack

Python 3, PyTorch, pytest, Sphinx

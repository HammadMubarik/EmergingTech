# Emerging Technologies Assessment

This repository contains my submission for the Emerging Technologies assessment. The core work is presented in `problems.ipynb`, with clear explanations, code, and outputs for all required problems.

## Target Audience

The notebook is written for an informed computing professional who can clone the repository and run the work with minimal setup.

## Repository Contents

- `problems.ipynb`: Main notebook containing solutions to Problems 1-5.
- `requirements.txt`: Python dependencies needed to run the notebook.
- `.gitignore`: Ignore rules for common Python/Jupyter temporary files.

## Quick Start

```bash
git clone https://github.com/HammadMubarik/EmergingTech.git
cd EmergingTech
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
jupyter notebook problems.ipynb
```

## Project Structure Conventions

- Keep `problems.ipynb` in the repository root.
- Put datasets in `data/` (if required).
- Put generated images/figures in `img/` (if required).
- Keep filenames lowercase and avoid spaces.

## Notes

- The notebook uses one level-1 title and level-2 headings for each problem.
- Markdown explanations are included throughout to explain decisions, methods, and results.
- References are provided in context and in a dedicated references section.

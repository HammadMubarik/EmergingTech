# Emerging Technologies Assessment

This repository contains my assessment submission for Emerging Technologies (Summer 25/26). The main submission file is `problems.ipynb`, which develops and demonstrates classical and quantum solutions for the required problem set.

## Assessment Scope

The notebook addresses all five required problems:

1. Generating random constant/balanced Boolean functions for four-bit inputs.
2. Classically determining whether a function is constant or balanced, including efficiency analysis.
3. Building and validating the four single-bit Deutsch oracles in Qiskit.
4. Implementing Deutsch's algorithm and demonstrating one-query classification.
5. Scaling to Deutsch-Jozsa for four-bit functions and verifying behavior on constant and balanced cases.

## Repository Structure

- `problems.ipynb` - Main submission notebook.
- `requirements.txt` - Python dependencies required to run the notebook.
- `.gitignore` - Ignore rules for Python/Jupyter and local development artifacts.

## Target Audience

The notebook is written for an informed computing professional. Explanations are included so that a technically strong reader can understand the approach, reproduce the results, and evaluate design decisions without further guidance.

## Environment and Dependencies

The project uses approved module dependencies listed in `requirements.txt`, including:

- `numpy`
- `qiskit[visualization]`
- `qiskit-aer`
- `matplotlib`
- `notebook`
- `ipykernel`

## Quick Start (macOS/Linux)

```bash
git clone https://github.com/HammadMubarik/EmergingTech.git
cd EmergingTech
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
jupyter notebook problems.ipynb
```

## Quick Start (Windows PowerShell)

```powershell
git clone https://github.com/HammadMubarik/EmergingTech.git
cd EmergingTech
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
jupyter notebook problems.ipynb
```

## Reproducibility Checklist

Before final submission or pushing major updates:

1. Open `problems.ipynb`.
2. Restart kernel.
3. Run all cells from top to bottom.
4. Confirm there are no errors.
5. Confirm outputs and execution order are clean.

## Documentation Approach

- One level-1 notebook heading for the title.
- One level-2 heading per problem.
- Level-3 subsections for method, implementation, testing, and discussion where appropriate.
- Markdown explanations and references included in context throughout the notebook.

## Notes for Reviewers

- Problem 5 includes explicit Deutsch-Jozsa demonstrations on two constant and two balanced four-bit functions.
- Classical and quantum outputs are compared to confirm correctness.
- References are included where concepts or implementation details rely on external documentation.

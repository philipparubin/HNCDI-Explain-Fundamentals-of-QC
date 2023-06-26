# HNCDI Explain: Introducing Quantum Algorithms

This repository contains files for the HNCDI Explain course, "Fundamentals of Quantum Computing: Introducing Quantum Algorithms".

There are two exercises:

1. ```grover-tutorial-<number>-exercise.ipynb``` Upload this file from within the IBM Quantum Lab. There are three Grover tutorials. Understand and implement Grover's searching algorithm.

2. ```shor-tutorial-exercise.ipynb``` Upload this file from within the IBM Quantum Lab. Understand and implement Shor's prime factorisation algorithm.

You can get this code in a few different ways, pick whichever you feel confident to do.

Either:
- **Clone:** Clone this respository and upload the exercise .ipynb files to the IBM Quantum Lab. Run all cells.
- **Download:** Go to Code > Download ZIP. Open the ZIP file and upload the .ipynb files to the IBM Quantum Lab. Run all cells.
- **Copy and Paste from GitHub:** Create a new notebook in the IBM Quantum Lab. Copy and paste the commands one cell at a time from the .ipynb files into your new notebook and run each cell with Shift-Enter.

### Local dev instructions (not for participants)

```
python -m venv .venv
pip install poetry
poetry install
```
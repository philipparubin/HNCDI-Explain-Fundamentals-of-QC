# HNCDI Explain: Introducing Quantum Algorithms

This repository contains files for the HNCDI Explain course, "Fundamentals of Quantum Computing: Introducing Quantum Algorithms".

There are two exercises:

1. ```grover-tutorial-<number>-exercise.ipynb``` There are three Grover tutorials. Understand and implement Grover's searching algorithm. Created by Michael Garn, [michael.garn@stfc.ac.uk]((mailto:michael.garn@stfc.ac.uk)).

2. ```shor-tutorial-exercise.ipynb``` Understand and implement Shor's prime factorisation algorithm. Created by Dilhan Manawadu, [dilhan.manawadu@stfc.ac.uk](mailto:dilhan.manawadu@stfc.ac.uk).

You can get this code in a few different ways, pick whichever you feel confident to do.

1. Use the provided links to load the notebooks in a Google Colab environment (Please note that you will require a Google account and an IBM quantum account),
    - Grover's algorithm
        * Tutorial 1: https://colab.research.google.com/github/philipparubin/HNCDI-Explain-Fundamentals-of-QC/blob/main/grover-tutorial-exercises/grover-tutorial-1-exercise.ipynb
        * Tutorial 2: https://colab.research.google.com/github/philipparubin/HNCDI-Explain-Fundamentals-of-QC/blob/main/grover-tutorial-exercises/grover-tutorial-2-exercise.ipynb
        * Tutorial 3: https://colab.research.google.com/github/philipparubin/HNCDI-Explain-Fundamentals-of-QC/blob/main/grover-tutorial-exercises/grover-tutorial-3-exercise.ipynb
    - Shor's algorithm
        * Shor's tutorial: https://colab.research.google.com/github/philipparubin/HNCDI-Explain-Fundamentals-of-QC/blob/main/shor-tutorial-exercise.ipynb
    - Exercise 1: https://colab.research.google.com/github/philipparubin/HNCDI-Explain-Beginners-Guide-to-QC/blob/main/1-bell-state-exercise-ibmq.ipynb
    - Exercise 2: https://colab.research.google.com/github/philipparubin/HNCDI-Explain-Beginners-Guide-to-QC/blob/main/2-pi-estimate-exercise.ipynb

2. Run it locally
    Either:
        - **Clone/Download:** Clone/Download this respository and load it using your favourite notebook environment. 
        - If you would like to run the simulator exercises on your local machine, you can use poetry for notebook requirements. 

### Local dev instructions (not for participants)

```
python -m venv .venv
pip install poetry
poetry install
```

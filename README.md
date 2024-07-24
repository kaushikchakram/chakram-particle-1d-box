# chakram-particle-1d-box

## This repository investigates the classic particle in a $1D$ box model from quantum mechanics.
This was a project that I submitted for a course in Scientific Computing during my Undergraduate Studies.

### The main file is called `chakram_project_final_notebook.ipynb`.
+ The main purpose of the report is to investigate the particle in a 1D box model in `python` using Object Oriented Programming (OOP).
+ It is coded such that it only uses basic lines of code and it particularly avoids the use of complicated functions.
+ It generates a random number between $0$ and $L$ for multiple iterations and it accepts/rejects based on a condition such that the resulting values follow the particle in a $1D$ box model.
+ It simulates multiple iterations such that the resulting values follow the particle in a $1D$ box model. These results are compared to those obtained in the following source: **Engel, Thomas. Thermodynamics, Statistical Thermodynamics, and Kinetics. Pearson Higher Ed, 2013.**
+ The Research question is aimed to arrive at results stated by the *correspondence principle*. The *correspondence principle* states that the differences between quantum and classical mechanics are lowered as the quantum number $n$ is very large. This report adresses this question through a `class` called `P1D` that runs the particle in a one-dimensional box simulation, which generates the probability density function as function of position over (i.e. divided by) the length $L$ of the box.

# Entanglement
Mahnaz Ghorbani, Shahin atashbar Tehrani


from pathlib import Path

readme = r'''# Quantum Correlations and Nonclassical Light in a Moving Two-Qutrit System

## Overview

This repository contains the **Wolfram Mathematica notebooks** used for the analytical and numerical investigation of quantum correlations and nonclassical properties of light in a system composed of **two moving three-level atoms (qutrits)** interacting with a quantized radiation field through a **nonlinear two-photon coupling**.

The notebooks accompany the manuscript:

> **Quantum Correlations and Nonclassical Light Generation in a Moving Two-Qutrit System with Nonlinear Two-Photon Coupling**

They provide the computational procedures used to evaluate several nonclassicality and entanglement indicators, including:

- Mandel parameter;
- Cauchy–Schwarz inequality;
- quadrature and sum squeezing;
- phase-entropic squeezing;
- atomic entanglement quantified by concurrence.

Making these notebooks publicly available is intended to improve the **transparency, reproducibility, and verifiability** of the reported results.

---

## Repository Contents

| Notebook | Description |
|---|---|
| `two moving threelevel atoms1_parameter mandel.nb` | Calculates the Mandel parameter and investigates the photon-number statistics of the radiation field. Negative values of the Mandel parameter indicate sub-Poissonian photon statistics and nonclassical behavior. |
| `Cauchy- Schwartz inequality.nb` | Evaluates the relevant Cauchy–Schwarz inequality criterion used to identify nonclassical correlations in the atom–field system. |
| `sum squeezing.nb` | Computes the sum-squeezing parameters and examines the squeezing behavior of the field during the time evolution of the system. |
| `entanglement between two atoms_Concurrence.nb` | Evaluates the entanglement between the two atoms using concurrence or the corresponding reduced atomic density matrix. |
| `Phase entropic squeezing.nb` | Calculates phase-entropic squeezing and analyzes the phase-related nonclassical properties of the field. |

---

## Physical Model

The calculations concern two moving three-level atoms interacting with a quantized field through a nonlinear two-photon transition. Depending on the formulation used in each notebook, the model may include effects such as:

- atomic motion;
- intensity-dependent atom–field coupling;
- two-photon transitions;
- nonlinear field interactions;
- detuning parameters;
- time-dependent quantum amplitudes;
- reduced atomic and field density matrices.

The explicit Hamiltonian, state vector, probability amplitudes, parameter definitions, and analytical expressions are given in the associated manuscript and implemented in the Mathematica notebooks.

---

## Requirements

The notebooks require:

- **Wolfram Mathematica** or **Wolfram Desktop**;
- a Mathematica version supporting standard symbolic, numerical, plotting, and linear-algebra functions;
- sufficient memory for symbolic simplification and numerical summation over the photon-number basis.

No external Mathematica packages are expected to be necessary unless explicitly imported inside an individual notebook.

---

## How to Use

1. Clone or download this repository:

   ```bash
   git clone https://github.com/USERNAME/REPOSITORY-NAME.git


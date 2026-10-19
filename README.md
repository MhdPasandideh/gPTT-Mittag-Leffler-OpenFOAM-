# Revisiting the Generalized Phan-Thien–Tanner Viscoelastic Model

This repository contains the LaTeX source code, Python plotting scripts, and the OpenFOAM (Rheotool) simulation case files for the paper:

**"Revisiting the Generalized Phan-Thien–Tanner Viscoelastic Model: Mathematical Analysis, Rheological Characterisation and Enhanced Junction-Dissipation Functions via a Three-Parameter Mittag-Leffler Kernel"**
*Authors: R. Henriques, L.L. Ferrás, M. Pasandidehpoor*
*Journal: Polymer Bulletin (Springer)*

## 📂 Repository Structure

* **`/manuscript`**: Contains the LaTeX source code (`polymer_bulletin.tex`) and all figures. To compile, you need the Springer Nature `sn-jnl.cls` and `sn-basic.bst` files (included).
* **`/python_scripts`**: Contains the Python scripts used to generate the analytical comparisons, transient shear overshoots, and normal stress profiles.
* **`/openfoam_case`**: Contains the OpenFOAM setup for the pipe/channel flow simulations.

## 💻 1. Python Scripts (Data & Figures)
The figures in the paper were generated using Python. 
### Requirements
You will need Python 3.8+ and the following libraries:
```bash
pip install numpy scipy matplotlib

# GW-GR-Test-ppE-formalism

# Gravitational-Wave Tests of General Relativity Using the ppE Formalism

This repository contains the code, notebooks, and report for a project exploring how deviations from General Relativity (GR) can be constrained using gravitational-wave observations. The work is based on the parametrized post-Einsteinian (ppE) framework and follows the methodology discussed in the referenced arXiv paper included in this project.

---

## Contents of This Repository

### 1. Project Report  
The PDF project report provides a structured explanation of the physics background, the ppE formalism, and how gravitational-wave phase corrections can be used to test GR.  
It includes:
- A summary of the theoretical framework  
- Derivations and equations used in the notebooks   
- Discussion of how deviations from GR map into observable waveform parameters  

---

### 2. Notebooks / Code

#### **(a) RZ_Metric_ppE_parameter_GW_Constraint.ipynb**  
This notebook focuses on the analytical part of the project:
- Derivation of ppE coefficients  
- Mapping between metric deviations and waveform phase corrections  
- Calculation of constraints for given deformation parameters  
- Symbolic and numerical checks  

#### **(b) ppE_GW_Constraints.ipynb**  
This notebook performs numerical evaluations and example parameter constraints:
- Applying ppE modifications to inspiral waveforms from GW datasets
- Translating ppE parameters into bounds using observational inputs  
- Plotting and analyzing resulting constraints on ppE parameter

In summary, the first .ipynb file is related to mathemtical derivation and the second .ipynb file is for constraining ppE parameters using observational datasets.

---

## Reference Paper (arXiv)

This project is primarily based on concepts and equations from these included arXiv papers:

**"Gravitational-wave versus X-ray tests of strong-field gravity" (arXiv:1912.08062)**  
**"Tests of General Relativity with the Binary Black Hole Signals from the LIGO-Virgo Catalog GWTC-1" (arxiv:1903.04467)**

The paper provides:
- Background on strong-field gravity tests  
- How gravitational waves probe deviations from GR  
- ppE-style parameterizations used for generic metric deformations  

(Of course, in the "Project Report", another mathematiical method to derive ppE parameters is included based on study of other papers and literature review.)

The dataset used here is LIGO LVC dataset.

---

## Purpose of This Project

The goal of this work is to:
- Understand how gravitational-wave signals encode deviations from Einstein’s gravity  
- Implement ppE corrections to the inspiral waveform  
- Derive constraints on generic deformation parameters from data  
- Build a clean, reproducible code base that others can extend  

This repository demonstrates the full workflow from theoretical setup, to derivations, to numerical constraint evaluation.

---

## Acknowledgment

This project relies on theoretical foundations from the referenced arXiv work and is intended purely for research, learning, and reproducibility.


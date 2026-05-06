# Shear-Strain-Dependent Thermal Conductivity of Diamond

This repository contains the machine learning potential and simulation scripts for the study: **"Shear-strain-dependent thermal conductivity of diamond explored via a machine learning potential"**.

## 1. Contents

- `01_generate_shear_model.py`: A Python script to generate shear-strained diamond supercells (4x4x4, 512 atoms) based on the primitive cell.
- `02_nep.txt`: The trained Neuroevolution Potential (NEP) file utilized in this study.
- `03_run_hnemd.in`: The input configuration file for GPUMD simulations using the HNEMD method.
- `04_post_process_kappa.m`: A MATLAB script for post-processing GPUMD output files to calculate the running thermal conductivity.

## 2. Usage (How to Reproduce)
1. Generate the structure: `python 01_generate_shear_model.py`
2. Run simulation: Use `03_run_hnemd.in` and `02_nep.txt` with **GPUMD 3.9+**.
3. Analyze results: Run `04_post_process_kappa.m` in MATLAB.

## 3. Citation
Please cite our paper if you use these materials:
[Insert your paper citation here]


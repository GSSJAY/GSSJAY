# Shear-Strain-Dependent Thermal Conductivity of Diamond

This repository contains the machine learning potential and simulation scripts for the study: **"Shear-strain-dependent thermal conductivity of diamond explored via a machine learning potential"**.

## 1. Contents

- `01_generate_shear_model.py`: A Python script to generate shear-strained diamond unit cells based on the primitive cell.
- `02_nep.txt`: The trained Neuroevolution Potential (NEP) file utilized in this study.
- `03_run_hnemd.in`: The input configuration file for GPUMD simulations using the HNEMD method.
- `04_post_process_kappa.m`: A MATLAB script for post-processing GPUMD output files to calculate the running thermal conductivity.

## 2. Usage (How to Reproduce)

1. **Generate the unit cell**: Run `python 01_generate_shear_model.py` to create the strained unit cell files.
2. **Run simulation**: Use `03_run_hnemd.in` and `02_nep.txt` with **GPUMD 3.9+**.
3. **Analyze results**: Run `04_post_process_kappa.m` in MATLAB to calculate thermal conductivity.

## 3. Citation

If you use these materials or the NEP potential in your research, please cite our work as follows:

**Paper (Under Review):**
> S. Guo, Q. Wang, Z. Qi, Z. Sun, B. Chen, R. Li, W. Shen, and G. Wu, "Shear-strain-dependent thermal conductivity of diamond explored via a machine learning potential," *Submitted* (2026).

**Code/Repository:**
> S. Guo, "Diamond-shear: Potentials and simulation scripts for diamond shear-strain thermal transport," GitHub (2026). Available at: https://github.com/wugai-whu/Diamond-shear

*Note: This citation will be updated with full journal information upon publication.*

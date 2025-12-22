# Molecular phylogenetics course
This repository contains materials for the EMBL **molecular phylogenetics course**, as part of the 2nd year EMBL PhD bioinformatics course. The material is organised around Jupyter notebooks for each of the 3 days of the project. See overview.pdf for more details about the scientific background and motivation for the project. Below guides you through how to use the repository and notebooks. 

## Repository structure

```
```

## Getting started

We recommend using **Visual Studio Code** or JupyterLab for exploring the notebooks.  To set up a working environment:

1. **Install Conda**: If you do not already have a conda distribution (e.g., Miniconda), install it from <https://docs.conda.io/en/latest/miniconda.html>.

2. **Clone the repository**: clone the workshop repo to your local machine
   ```bash
   git clone https://https://github.com/charlotte-west/mol_phy_course.git

   cd mol_phy_course
   ```
3. **Create an environment**: Use the provided `requirements.yaml` to create a reproducible environment:

   ```bash
   conda env create -f requirements.yaml
   conda activate mol_phy_course
   ```
   The `requirements.yaml` file lists the core dependencies.  Feel free to install additional packages manually. 
   
   You might need to upgrade jupyter:
   ```bash
   pip install --upgrade notebook jupyter_server jupyterlab jupyter_core traitlets
   ```

4. **Launch notebooks**: Open the notebooks folder in VS Code or run

   ```bash
   jupyter notebook notebooks/
   ```

## Course overview

### Day 1: Alignment

### Day 2: Phylogenetic inference

### Day 3: Phylodynamics


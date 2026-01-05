# Molecular phylogenetics course
This repository contains materials for the EMBL **molecular phylogenetics course**, as part of the 2nd year EMBL PhD bioinformatics course. The material is organised around a PDF document detailing tasks for two main modules:

## Course overview
- Module 1: Alignment
- Module 2: Phylogenetic inference and analysis

There is a Jupyter notebook for the first module to help get you started. See overview.pdf for more details about the scientific background and motivation for the project. Below guides you through how to use the repository and notebook. 


## Getting started

We recommend using **Visual Studio Code** or JupyterLab for using the notebook. VSCode is also recommended for working through the tasks and code development outside of the module 1 notebook. To set up a working environment:

1. **Install Conda**: If you do not already have a conda distribution (e.g., Miniconda), install it from <https://docs.conda.io/en/latest/miniconda.html>.

2. **Clone the repository**: clone the workshop repo to your local machine
   ```bash
   git clone https://https://github.com/charlotte-west/mol_phy_course.git

   cd mol_phy_course
   ```
   If you want to keep all of your code within this repository, we recommend creating your own git branch for developing your code, as you will not be able to push edits to the main branch.

   ```bash
   git checkout -b my_branch_name
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

4. **Launch notebooks**: Open the notebooks folder in VSCode or run

   ```bash
   jupyter notebook notebooks/
   ```



# CPBS7602

For assignment01:
- process the code in the jupiter notebooks starting from step1 to step 4
- data was processed outside of the local machine and a pickle file was generated and imported. Local machine has an intel i7 (12th gen) with 16 GB of RAM and a clean Ubuntu Nobel (v22) with surface pro 9 kernel (v6.9) distribution install.
  
update: this data has now been processed on a Macbook M4 Pro with 24 GB of RAM. See assignment 2 for the updated data preparation.
  
- environment file is shared across the repository (see cpbs7602.yml) and was installed via terminal after miniconda3 install.
        conda env create --file {path_to_cpbs7602_yaml}
For conveinence, the contents of the environment file are listed at the bottom of the README. 

---
For assignment03: 
- process this code in the jupyter notebook using the tpm_scaled data, the sample_key.csv, and the subject_phenotypes.txt files.
- as with assignment01, the environment file should have all packages needed.
- process the dimensionality reduction, then the tissue model, then the age model.
---

name: cpbs7602
channels:
  - conda-forge
  - defaults
dependencies:
  - ipython=8.*
  - ipywidgets
  - jupyterlab=4.2.*
  - jupyter_contrib_nbextensions=0.7.*
  - jupytext=1.*
  - matplotlib=3.9.*
  - nodejs=22.*
  - pandas=2.2.*
  - pandoc=3.*
  - pip
  - pre-commit=4.0.*
  - python=3.12.*
  - pyyaml=6.*
  - scipy=1.14.*
  - seaborn=0.13.*
  - scikit-learn=1.5.*
  - statsmodels=0.14.*
  - tqdm=4.*
  - umap-learn


# Code-snippets for data loading and processing

This repository contains a collection of notebooks that demonstrate various techniques for loading and processing data. The goal is to have an easy and fast access to code that can be reused in different projects.


## Notebooks

### CESM2_LE

<a target="_blank" href="https://colab.research.google.com/github/ckaramp-research/code-snippets/blob/main/CESM2_LE/ncar_cesm2le.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a> 
    
    How to load CESM2 Large Ensemble (CESM2-LE) data from AWS.

### CMIP6

<a target="_blank" href="https://colab.research.google.com/github/ckaramp-research/code-snippets/blob/main/CMIP6/cmip_catalog.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

    How to access CMIP6 data hosted on Google Cloud.

<a target="_blank" href="https://colab.research.google.com/github/ckaramp-research/code-snippets/blob/main/CMIP6/cmip_esgf.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

    How to access CMIP6 data from ESGF nodes using rooki.

### OBS_IRI

<a target="_blank" href="https://colab.research.google.com/github/ckaramp-research/code-snippets/blob/main/OBS_IRI/online_datasets.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

    How to access data downloaded and hosted in IRI library and other sources that support OPeNDAP.


## Running locally

If you feel more comfortable using your computer instead of the cloud, you can run the notebooks locally by using the provided `env.yml` file (or just installing the missing packages if you already have an environment).

1. Download the conda-installer that suits your OS from [here](https://conda-forge.org/download/)
2. Install mamba (faster than conda)
3. Create a new environment using the `env.yml` file with the following command:

    ```bash
    mamba env create -f env.yml
    ```
4. Activate the environment:

    ```bash
    conda activate climate
    ```
5. Launch Jupyter Lab or use Visual Studio Code to open the notebooks.
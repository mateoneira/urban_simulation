# Urban Simulation Practicals

This repository contains material related to CASA's Urban Simulation module. 

### Dependencies 

To set up your python environment to run the code in this repository, follow the instructions below.

1. Download and install (anaconda)[https://www.anaconda.com/]
2. Install Jupyter Notebook
    ```bash
    conda install -c conda-forge notebook
    ```
3. Create (and activate) a new environment with python 3.6
    - __Linux__ or __Mac__: 
    ```bash
    conda create --name urbsim --file=environment.yml
    source activate urbsim
    ```
    - __Windows__: 
    ```bash
    conda create --name urbsim --file=environment.yml
    ```
4. Create a [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `urbsim` environment.  
    ```bash
    python -m ipykernel install --user --name urbsim --display-name "urbsim"
    ```
5. Before running code in a notebook, change the kernel to match the `urbsim` environment by using the drop-down `Kernel` menu. 

![Kernel][kernel.jpg]

# Urban Simulation Practicals

### Dependencies 

To set up your python environment and run the code in the practicals, follow the instructions below.

1. Download and install [anaconda](https://docs.anaconda.com/anaconda/install/).
2. Download and unzip the material from Friday practical sessions week 1.
3. Open command prompt (or terminal if on Mac).
4. In the command prompt (or terminal) navigate to the directory where you unzipped the file. This folder contains an environment.yml file: example bellow.
    
    ```
    cd C:\Users\username\git\urban_simulation
    ```

5. Install Jupyter Notebook if not already installed.

    ```
    conda install -c conda-forge notebook
    ```

7. Create a new environment using the environment.yml file and activate the environment.
    - __Linux__ or __Mac__: 
    
    ```
    conda env create -f environment_mac.yml 
    source activate urbsim
    ```

    - __Windows__: 
    
    ```
    conda env create -f environment.yml 
    activate urbsim
    ```

8. Create a [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `urbsim` environment. 
 
    ```
    python -m ipykernel install --user --name urbsim --display-name "urbsim"
    ```

10. Launch jupyter notebook.

    ```
    jupyter notebook
    ```

11. Before running code in a notebook, change the kernel to match the `urbsim` environment by using the drop-down `Kernel` menu. 

![Kernel](https://raw.githubusercontent.com/mateoneira/urban_simulation/main/kernel.png)

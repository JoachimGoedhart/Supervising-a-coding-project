## Command line code for running Python

This is a list of (poorly organized) command line code for running python and managing environments:

### To test installation type:

`conda env list`

--------

### Creating and activating environments

`conda create --name first_env`

`conda activate first_env`

### Installing a package

`conda install numpy`


-----------------------

### Napari

These instructions come from the napari website: [https://napari.org/stable/tutorials/fundamentals/installation.html](https://napari.org/stable/tutorials/fundamentals/installation.html)

`conda create -y -n napari-env -c conda-forge python=3.9`

`conda activate napari-env`

`conda install -c conda-forge napari`

`napari`

-------------

### To list the environments:

`conda env list`

### To list packages in an environment (here first_env):

`conda list --name first_env`

### To remove an environment (here first_env):

`conda env remove -n first_env`


-----------------------------
### Creating an environment from a .yml file:

`conda env create -f environment_unmix.yml`

### To activate this environment, use:

`conda activate unmix_env`

### To deactivate an active environment, use:

`conda deactivate`


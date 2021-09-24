# 1RT705APML-Project
Code for Advanced Probabilistic Machine Learning Project. 

## Anaconda Environment
To organise the libraries utilised in our project. A anaconda environment is stored in the file "environment.yml". 

For a deeper explanation of managing environments. see the documentation [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).

### Setting up environment from file

Open anaconda command line and type 

> `conda env create -f environment.yml`

Anaconda will then set up a environment with the packages specifiedin the .yml file

Finally, activate the environment

> `conda activate APML

### Updating environment

If you need to install another package, update the environment.yml file manually and use the command

> `conda env update --file environment.yml  --prune`

The --prune option causes conda to remove any dependencies that are no longer required from the environment.

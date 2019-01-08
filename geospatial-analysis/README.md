# Geospatial analysis

This repository contains Jupyter notebooks to explore the Python ecosystem for geospatial analysis.

## Installation notes

The tutorials require several packages. 

To run it, you have a few options:

   1. If you like to use conda, install miniconda (instructions [here](https://conda.io/miniconda.html)). Then run
    ```
    conda env create -n carto_env -f environment.yml
    ```
    and 
    ```
    source activate carto_env
    ``` 
    to activate the environment. 
    Then run 
    ```
    jupyter notebook
    ``` 
    to start the notebook.

   2. If you're more of a pipenv person, create a virtual env, then run:
    ```
    pip install -r requirements.txt
    ```
    Then run 
    ```
    jupyter notebook
    ``` 
    to start the notebook.

## Downloading the tutorial materials

We would highly recommend using git, not only for these tutorials, but for the general betterment of your life. Once git is installed, you can clone the material in this repository by using the git address shown above:
```
git clone git://github.com/makinacorpus/tutorials/geospatial-analysis
```
If you can't or don't want to install git, there is a link above to download the contents of this repository as a zip file. We may make changes to the repository, however, so cloning the repository is a much better option.

## Notebook listing

You can view the tutorial materials using the excellent [nbviewer](https://nbviewer.jupyter.org/github/makinacorpus/tutorials/blob/master/geospatial-analysis/notebooks/Index.ipynb) service.

Note, however, that you cannot modify or run the contents within nbviewer. To modify them, first download the tutorial repository, change to the notebooks directory, and run ipython notebook. You should see the list in the ipython notebook launch page in your web browser. For more information on the IPython notebook, see http://ipython.org/notebook.html


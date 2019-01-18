# Machine Learning

This repository contains Jupyter notebooks to explore the Python ecosystem for machine learning.

## Installation notes

The tutorials require several packages. 

To run it install miniconda (instructions [here](https://conda.io/miniconda.html)). 

Create the relevant virtual env 
 ```
 conda env create -n tutorial_ml_env -f environment.yml
 ```
Activate it 

 ```
 source activate tutorial_ml_env
 ``` 
 
Install ipykernel
 
```
pip install ipykernel
```

Make virtual env avalaible in Jupyter notebook

```
python -m ipykernel install --user --name=tutorial_ml_env
```

Run juyter notebook 

 ```
 jupyter notebook
 ``` 
Open a tutorial notebook and select the kernel **tutorial_ml_env**

We would highly recommend using git, not only for these tutorials, but for the general betterment of your life. Once git is installed, you can clone the material in this repository by using the git address shown above:

```
git clone git://github.com/makinacorpus/tutorials/machine_learning
```
If you can't or don't want to install git, there is a link above to download the contents of this repository as a zip file. We may make changes to the repository, however, so cloning the repository is a much better option.
repository


## Notebook listing

You can view the tutorial materials using the excellent [nbviewer](https://nbviewer.jupyter.org/github/BerengereMathieu/tutorials/tree/master/machine_learning/) service.

Note, however, that you cannot modify or run the contents within nbviewer. To modify them, first download the tutorial repository, change to the notebooks directory, and run ipython notebook. You should see the list in the ipython notebook launch page in your web browser. For more information on the IPython notebook, see http://ipython.org/notebook.html

In addition, for storage and licence reasons, our machine learning notebooks are often provided withou data. At the beginning of these notebooks you will find information to download required data.


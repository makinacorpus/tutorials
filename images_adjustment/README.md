# Computer vision for images adjustment by homography - tutorial

## 1. Two options to launch the tutorial notebook
### 1.1 Create your virtual environment with environment.yml and Conda

Create your virtual environment, given the requirements reported in `environment.yml`:  
```bash
conda env create -n adjustment_env -f environment.yml
```

### 1.2 Install manually your own virtual environment
Requirements:
* OpenCV
    * with pip:  
    ```bash
    pip install opencv-python
    pip install opencv-contrib-python
    ```
    * with conda: `conda install -c menpo opencv`

* Numpy
    * with pip: `pip install numpy` 
    * with conda: `conda install -c anaconda numpy`

* Matplotlib
    * with pip: `pip install matplotlib` 
    * with conda: `conda install -c conda-forge matplotlib`

* iPyWidgets
    * with pip: `pip install ipywidgets`
    * with conda: `conda install -c anaconda ipywidgets`

## 2. Launch the notebook

Activate your virtual environment (named `adjustment_env` in the following code lines):  
```bash
conda activate adjustment_env
```

Add this virtual environment to the environments list in Jupyter:
```bash
python -m ipykernel install --user --name=adjustment_env
```

Run Jupyter notebook:
```bash
jupyter notebook
```

A new page should open in your browser and list the files in your folder. The notebook `images_adjustment.ipynb` shoud appear in the list. Open it and, in Kernel menu, go to `Change kernel` and select the `adjustment_env`.

You can now start following the tutorial.
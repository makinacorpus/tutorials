# Flooding detection on Sentinel2 images

### 1. Two options for virtual environment setting
#### 1st option: Create your virtual environment from `environment.yml` and Conda

Create your virtual environment, given the requirements reported in `environment.yml`:  
```bash
conda env create -n flooding_env -f environment.yml
```

#### 2nd option: Install manually your own virtual environment
Requirements:
* [`rasterio`](https://rasterio.readthedocs.io/en/latest/)
* [`geopandas`]()
* [`folium`](https://python-visualization.github.io/folium/index.html)
* [`fiona`](https://fiona.readthedocs.io/en/latest/)
* [`numpy`](https://numpy.readthedocs.io/en/latest/)
* [`folium`](https://python-visualization.github.io/folium/index.html)
* [`matplotlib`](https://matplotlib.org/)


### 2. Set the environment as Jupyter kernel

Activate your virtual environment (named `flooding_env` in the following code lines):  
```bash
conda activate flooding_env
```

Add this virtual environment to the kernels available Jupyter:
```bash
python -m ipykernel install --user --name=flooding_env
```

Check if the environment appears in the kernels list:
```bash
jupyter kernelspec list
```

### 3. Launch the notebook
Run Jupyter notebook:
```bash
jupyter notebook
```

A new page should open in your browser and list the files in your current directory. The notebook `flooding_detection.ipynb` shoud appear in the list. Open it and, in Kernel menu, go to `Change kernel` and select the `flooding_env`.

You can now start following the tutorial. Enjoy!
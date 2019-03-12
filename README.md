# walnut-canopy-measurement-pipeline
Image processing pipeline for quantifying walnut canopy phenotypes.

### Notes

- Note that `conda install` is preferred over `pip install` for ease of update to `environment.yml` with the command `conda env export > environment.yml`.
- In order to use a Jupyter Notebook within Conda environment first need to install the following Conda channel:
`conda install --channel=conda-forge nb_conda_kernels`. Once within your activated Conda environment, run `conda install ipykernel`.
- Numpy 1.16 and Skimage 0.14.2 are incompatible. Had to downgrade Numpy to 1.15. (https://github.com/scikit-image/scikit-image/issues/3586)

### Resources
- Tutorial: https://towardsdatascience.com/object-detection-with-neural-networks-a4e2c46b4491

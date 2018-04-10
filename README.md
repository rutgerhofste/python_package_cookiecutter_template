# python_package_cookiecutter_template
Create a python package with Cookiecutter

# Create a Python Package using CookieCutter. 

This repo uses the official [tutorial](https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html)

Notes are copied below.  


conda create -n python35cookiecutter python=3.5
source activate python35cookiecutter
conda config --add channels conda-forge
conda install cookiecutter

cookiecutter https://github.com/audreyr/cookiecutter-pypackage.git
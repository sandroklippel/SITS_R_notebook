# SITS_R_notebook
A Jupyter notebook to demonstrate SITS package.

## DEPENDENCIES
This notebook depends on the SITS R package => https://github.com/e-sensing/sits

## Notebook setup Ubuntu 16

```bash
# python setup
conda update conda
conda create --name geospatial python=2.7
source activate geospatial
conda install ipykernel
conda install nb_conda
# R setup
R                                                       # start an R session
install.packages('devtools')
devtools::install_github('IRkernel/IRkernel')
IRkernel::installspec() 
quit()                                                  # finish R session
# notebook setup
python -m ipykernel install --user --name geospatial --display-name "Python [geospatial]"
git clone https://github.com/e-sensing/SITS_R_notebook
cd SITS_R_notebook
jupyter notebook SITI_R_notebook.ipynb
```


## Notebook setup

```bash
conda update conda
conda create --name geospatial python=2.7
source activate geospatial
conda install ipykernel
conda install nb_conda
python -m ipykernel install --user --name geospatial --display-name "Python [geospatial]"
git clone https://github.com/e-sensing/SITS_R_notebook
jupyter notebook
```


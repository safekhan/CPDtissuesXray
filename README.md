# CPDtissuesXray
The code in this repo supports the plots and findings presented in this study:

> **Critical point drying of brain tissues for X-ray phase contrast imaging**
> 
> Safe Khan, Jonas Albers, Artem Vorobyev, Yuxin Zhang, Jakob Reichmann, Angelika Svetlove, Fabio de Marco, Ksenia Denisova, Yikai Yang, Florent Seichepine, James Douglas, Elizabeth Duke, Peter Cloetens, Alexandra Pacureanu, Andreas T. Schaefer & Carles Bosch.
> 
> bioRxiv 2025.

Frozen record of the code version 1.0.0 released with the revised manuscript: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17035301.svg)](https://doi.org/10.5281/zenodo.17035301)


## Analyses
### Getting started
1. clone this repo
2. create a [conda environment]() with the essential packages
```
conda create -n my_env python=3.8.16 numpy=1.23.5 pandas=1.5.2 scipy=1.10.0 matplotlib seaborn jupyter
```
3. start jupyter in this conda environment
```
conda activate my_env
jupyter notebook
```
4. check the paths to the repo in the [main scripts](https://github.com/safekhan/CPDrOTOPaper/tree/main/notebooks) work in your setup.
5. run the jupyter notebook scripts to reproduce the plots.


## Datasets
### All tomograms

All datasets reported in this study (X-ray phase contrast tomographic reconstructions) can be accessed [here](https://github.com/safekhan/CPDrOTOPaper/blob/main/data/tomogram_list.md).

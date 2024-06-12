# Matchms user documentation

This is the user documentation for the [matchms project](https://github.com/matchms/matchms). It is available in HTML and PDF at [https://matchms.github.io/matchms-docs](https://matchms.github.io/matchms-docs)

## Create environment
To run the jupyter notebooks its best to create a seperate Conda environment by

    conda create --name matchms python=3.9
    conda activate matchms
    conda install --channel bioconda --channel conda-forge matchms

You may need to install additional packages from the matchms ecosystem like e.g., [Spec2Vec](https://github.com/iomega/spec2vec). The dependencies are listed in the notebooks.

```{tableofcontents} 
```

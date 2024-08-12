![logo](bifacialfield.png)

# NREL Bifacial Experimental Single-Axis Tracknig (BEST) Field Degradation Research

## Introduction

This repository contains a series of functions and jupyter notebooks used to explore the various data available for the bifacial test site at NREL.
Performance Datasets can be found here:
Measurements of the modules can be found here:

Tutorials
=========

### Jupyter Book

For in depth Tutorials you can run online, see our [jupyter-book](https://DuraMAT.github.io/Best-Field-Degradation-Research/intro.html) [![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://DuraMAT.github.io/Best-Field-Degradation-Research/intro.html)

Clicking on the rocket-icon on the top allows you to launch the journals on [Google Colaboratory](https://colab.research.google.com/) for interactive mode.
Just uncomment the first line `pip install ...`  to install the environment on each journal if you follow this mode.

### Binder

To run these tutorials in Binder, you can click here:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DuraMAT/Best-Field-Degradation-Research/main)
It takes a minute to load the environment.

### Locally

You can also run the tutorial locally in a virtual environment, i.e., `venv` or
[miniconda](https://docs.conda.io/en/latest/miniconda.html).

1. Create and activate a new environment, e.g., on Mac/Linux terminal with `venv`:
   ```
   python -m venv Best-Field-Degradation-Research
   . pvdeg/bin/activate
   ```
   or with `conda`:
   ```
   conda create -n Best-Field-Degradation-Research
   conda activate Best-Field-Degradation-Research
   ```

1. Start a Jupyter session:

   ```
   jupyter notebook
   ```

1. Use the file explorer in Jupyter lab to browse to `tutorials`
   and start the first Tutorial.

## License

This open source code is copyrighted by the Alliance for Sustainable Energy and licensed with BSD-3-Clause terms, found [here](https://github.com/DuraMAT/Best-Field-Degradation-Research/blob/master/LICENSE).

## Getting Support

If you suspect that you may have discovered a bug or if you'd like to
change something about Best-Field-Degradation-Research, please make an issue on our
[GitHub issues page](https://github.com/DuraMAT/Best-Field-Degradation-Research/issues).

## Citing

If you use Data from the Bifacial Field in a published work, please cite:

    S. Ovaitt, “BEST field data,” DuraMAT Datahub, Sep. 30, 2022, doi: 10.21948/1787805

This repository can be cited as:

    Ovaitt, Olsen, Deline, et al "Best-Field-Degradation-Research, Version 0.0.1", Zenodo DOI:

Please also cite the DOI corresponding to the specific version used; DOIs are listed at [Zenodo.org](https://zenodo.org/search?page=1&size=20&q=conceptrecid:3860349&all_versions&sort=-version)

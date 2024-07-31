![logo](images/bifacialfield.png)

# NREL Bifacial Field_Measurements

## Introduction

This repository contains a series of functions and jupyter notebooks used to explore the various data available for the bifacial test site at NREL.
Performance Datasets can be found here:
Measurements of the modules can be found here:

Tutorials
=========

### Jupyter Book

For in depth Tutorials you can run online, see our [jupyter-book](https://nrel.github.io/PVDegradationTools/intro.html) [![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://nrel.github.io/PVDegradationTools/intro.html)

Clicking on the rocket-icon on the top allows you to launch the journals on [Google Colaboratory](https://colab.research.google.com/) for interactive mode.
Just uncomment the first line `pip install ...`  to install the environment on each journal if you follow this mode.

### Binder

To run these tutorials in Binder, you can click here:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NREL/PVDegradationTools/main)
It takes a minute to load the environment.

### Locally

You can also run the tutorial locally in a virtual environment, i.e., `venv` or
[miniconda](https://docs.conda.io/en/latest/miniconda.html).

1. Create and activate a new environment, e.g., on Mac/Linux terminal with `venv`:
   ```
   python -m venv NRELBifacialFieldMeasurements
   . pvdeg/bin/activate
   ```
   or with `conda`:
   ```
   conda create -n NRELBifacialFieldMeasurements
   conda activate NRELBifacialFieldMeasurements
   ```

1. Start a Jupyter session:

   ```
   jupyter notebook
   ```

1. Use the file explorer in Jupyter lab to browse to `tutorials`
   and start the first Tutorial.


## Contributing

We need your help to make bifacial_radiance a great tool! Please see the [Contributing page](https://bifacial-radiance.readthedocs.io/en/stable/contributing.html) for more on how you can contribute. The long-term success of bifacial_radiance requires substantial community support.

## License

This open source code is copyrighted by the Alliance for Sustainable Energy and licensed with BSD-3-Clause terms, found [here](https://github.com/NREL/bifacial_radiance/blob/master/LICENSE).

## Getting Support

If you suspect that you may have discovered a bug or if you'd like to
change something about NREL_Bifacial_Field_Measurements, please make an issue on our
[GitHub issues page](https://github.com/Duramat/NREL_Bifacial_Field_Measurements/issues).

## Citing

If you use Data from the Bifacial Field in a published work, please cite:

    Ayala Pelaez and Deline, (2020). bifacial_radiance: a python package for modeling bifacial solar photovoltaic systems. Journal of Open Source Software, 5(50), 1865, https://doi.org/10.21105/joss.01865

This repository can be cited as:

    Ovaitt, Olsen, Deline, et al "NREL_Bifacial_Field_Measurements, Versoin 0.0.1", Zenodo DOI:

Please also cite the DOI corresponding to the specific version used; DOIs are listed at [Zenodo.org](https://zenodo.org/search?page=1&size=20&q=conceptrecid:3860349&all_versions&sort=-version)

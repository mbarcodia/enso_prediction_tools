# ENSO Nino3.4 Index Prediction Tools

A classification and a regression tool built to predict the phase of ENSO and the value of the Nino3.4 Index, respectively. The classification tool predicts the ENSO phase at a specified lead given the Nino3.4 Index. The regression tool predicts the value of the Nino3.4 Index at a specified lead, given the Nino3.4 Index and a specified number of lagged steps. This tool was designed specifically to test the effects of various (and invalid) preprocessing steps. 

These tools are also used as part of a tutorial given by CSU for NC A&T. The full tutorial Github can be found at <https://github.com/eabarnes1010/ml_tutorial_ncat>. 

## Requirements & Specifications

### Code

Code is written in pytorch.

### Environment

This code was created to run in Google Colaboratory <https://colab.research.google.com/>. All you should need is a Google account.

Unless otherwise stated, code was additionally tested on local machines using the following environment.
```
conda create --name env-enso-preprocessing python=3.12.0
conda activate env-enso-preprocessing
conda install numpy scipy pandas matplotlib xarray scikit-learn netCDF4 cartopy pytorch
conda install  palettable flake8  jupyterlab black jupyterlab_code_formatter
pip install ipykernel seaborn cartopy fsspec requests aiohttp h5netcdf wget
```

## Additional Information

### Credits

These tools were built by Marybeth Arcodia for a publication to be submitted to the Bulletin of the American Meteorological Society. The full citation for the article will be listed upon acceptance. 

### License

This project is licensed under an MIT license.
MIT © [Marybeth C. Arcodia](https://github.com/mbarcodia)

# Trying tropycal

Python package 'tropycal' looks promising and I want to try it out.  Since it has a slew of dependencies, I am making a new
repo so that the other notebooks don't need all those packages in their environment.

tropycal
- https://tropycal.github.io/tropycal/index.html

dependencies
- matplotlib >= 2.2.2
- numpy >= 1.14.3
- scipy >= 1.1.0
- pandas >= 0.23.0
- xarray >= 0.10.7
- networkx >= 2.0.0
- pyshp >= 2.1
- cartopy >= 0.17.0

And the environment will also have:
- tropycal

Then I added netCDF so I could plot MUR SST
- netcdf4

Click on the Binder button to open the Notebook:

Try out tropycal commands:
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mas300labs-uofsa/try-tropycal/HEAD?labpath=index.ipynb)

Plot Sally's path, with wind, pressure from HURDAT2 and sea surface temperature from MURS:
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mas300labs-uofsa/try-tropycal/HEAD?labpath=hurdat_murs.ipynb)

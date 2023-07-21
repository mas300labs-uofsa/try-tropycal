# Trying Tropycal

Python package 'tropycal' looks promising and I want to try it out.  Since it has a slew of dependencies, I am making a new
repo so that the other notebooks don't need all those packages in their environment.  The dependencies for Binder are in [environment.yml](environment.yml).

## Tropycal examples and AMS talk

Check official Tropycal examples in my forked repo [sample-scripts](https://github.com/lisalenorelowe/sample-scripts).  The AMS talk had some deprecated function calls, so my fork has those fixed.  Those Notebooks should all work as advertised, with caveats listed in the README.

## Notebook for trying commands
First, see
- [Tropycal Website](https://tropycal.github.io/tropycal/index.html)
- [Examples for individual storm analysis](https://tropycal.github.io/tropycal/examples/tracks.storm.html)

Click on the Binder button to open the Notebook:

Try out tropycal commands:
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mas300labs-uofsa/try-tropycal/HEAD?labpath=index.ipynb)

## Notebook for Hurricane Sally(2020)
Plot Sally's path, with wind, pressure from HURDAT2 and sea surface temperature from MURS:
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mas300labs-uofsa/try-tropycal/HEAD?labpath=hurdat_murs.ipynb)

## Warning

Binder VMs are limited to either 2GB or 4GB RAM.  If your analysis seems slow, check the memory utilization at the bottom.  If you are maxing out the memory, run the Notebook locally by using miniconda to create an environment for tropycal+Notebook. A YAML file for creating the environment is included in this repo: env_try-tropycal.yml.

If conda is already installed, you can do:
```
git clone https://github.com/mas300labs-uofsa/try-tropycal
cd try-tropycal
conda env create ~/env_try-tropycal -f env_try-tropycal.yml
conda activate ~/env_try-tropycal
jupyter-notebook hurdat_murs.ipynb
```

All bets are off for Windows machines just yet...

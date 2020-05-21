# Open TV Data Analysis
*Authored by [Scott Cambo](http://www.scottallencambo.com)*

This Github repository includes all code for use in analyzing data collected to promote and research 
the [Open TV Platform for Intersectional Television](https://ajchristian.org/projects/#/open-tv-beta)
that is lead by [Professor AJ Christian](https://ajchristian.org/) of Northwestern University.

# Important Resources
### [OTV Bible](https://docs.google.com/document/d/1UILj0y_OTnWyv1QIfBcDpczUQdF7CesVnUoC_KNSTgc/edit?ts=5e174da0#)
The OTV Bible includes information important to research assistants of the OTV project.

### [OTV Research Plan](https://docs.google.com/document/d/1VR-LG5srw26tv3r2tFKOtD4WhOhTwcgwM7e4Kv29BgU/edit)
The OTV Research Plan is a roadmap for the research efforts which utilize the social media and marketing
data being collected about OTV.

# Downloading and organizing the **data**
1. Ask Professor Christian for access to the Dropbox if you don't already have access to it.
2. In the `Data Collection` dropbox folder go to `Spreadsheets`, i.e. `/Data Collection/Spreadsheets/`
3. Download the data for the years of interest and unzip them to the `./data` folder
    * For example, when unzipped you should be able to access the data for the April 3rd to May 1st period of 2019 in its own folder by navigating to `/data/Spreadsheets_2019/Spreadsheets (04_03_2019)-(05_01_2019)/`

# Recommended Work Environment Configuration
* All the jupyter notebooks in this repository were composed using Python 3.6+
* Data analysis should be done using [virtual environments](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) to avoid work configurations that may conflict with general system configurations.
    * `virtualenv` is the most basic virtual environment configuration tool, but I recommend using a combination of [`Pyenv`](https://github.com/pyenv/pyenv), which manages multiple python version installations, and [`Pipenv`](https://pipenv.readthedocs.io/en/latest/), which manages the virtual environment in a way that is more easily reproducible in different system environments. I have found [***this blog post***](https://hackernoon.com/reaching-python-development-nirvana-bb5692adf30c) to be the most helpful in configuring these two together.
    * ***Important Note for Windows users***: Pyenv is not compatible with Windows. That is okay, it's not entirely necessary (especially for Windows). Consider following [this blog post](https://docs.python-guide.org/starting/install3/win/) instead for installing Python 3 and setting up *Pipenv*. 
* Most (if not all) of the computational analysis will be done using [Jupyter](https://jupyter.org/). With the virtual environment active, follow the directions on Jupyter's website to install either Jupyter notebook or Jupyter lab. Jupyter notebook is designed for simpler projects in which only one or two notebooks are of importance
for analysis at a given time and Jupyter lab is designed for larger, more complex project which require that many files and directories are managed in the same interface.

# Research Questions:
* What are our most popular series by year (views and loads)? Excluding *Brown Girls* & *Brujos*?
* What sites refer the most traffic to OTV projects? By year as well.
* What projects have the highest retention rates (average percentage watched)? By year as well.
* What projects feature the most engagement (comments and likes)? By year as well.
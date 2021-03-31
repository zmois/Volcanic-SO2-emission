**Code Louisville Data Science with Python Project**<br>
This project is studying the impact of Volcanic Gases (SO<sub>2</sub> emission) on weather in Italy, using Etna volcano as an example. This is not a science project, but a small Data Science project that used a limited data - please don’t judge too hard.

All data about volcanoes comes from Smithsonian Institution Natural Museum of Natural History Global Volcanism Program
https://volcano.si.edu/

All historical climate data from the Climate Change Knowledge Portal by the World Bank Group
https://climateknowledgeportal.worldbank.org/

## Requirements
- Python 3.7 or newer. To check the installed version type `python3 –version` in the command line. The latest Python version can be installed from here.
- Conda 4.9.2

## Installation
1. Clone or Download the project `git clone https://github.com/zmois/Volcanic-SO2-emission`
2. The easiest way to install Jupyter Notebooks is to download and install the Anaconda distribution of Python. The Anaconda comes with Jupyter Notebook included and no further installation steps are necessary. Download the "Anaconda" software https://www.anaconda.com/products/individual#download-section
3. Create a new virtual environment in Anaconda Navigator, step-by-step instructions can be found here https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/
Next, install all the packages listed above manually
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- geopandas

Alternative to Anaconda Navigator is to use terminal for creating and activating the virtual environment with conda and requirements.txt
`conda create --name <env> --file requirements.txt`

## Running Jupyter Notebook
1. From the Navigator's home click on the "Launch" button under Jupyter tab. This will open jupyter on a browser.
2. Go in a working directory (choose the folder name or create a new one) and copy in there the jupyter notebook code examples (.ipynb files plus the input data file when needed). 
 Or
Launch Jupyter Notebook in the terminal with `jupyter notebook` command.


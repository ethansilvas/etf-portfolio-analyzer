# Module 7 Challenge - ETF Portfolio Analysis Using SQLAlchemy and hvPlot



**Data from 2016-2020** <br>
[ETF timestamped OHLCV database](/etf.db)

---

## Technologies

This is a Python 3.7 project ran using a JupyterLab in a conda dev environment. 

The following dependencies are used: 
1. [Jupyter](https://jupyter.org/) - Running code 
2. [Conda](https://github.com/conda/conda) (4.13.0) - Dev environment
3. [Pandas](https://github.com/pandas-dev/pandas) (1.3.5) - Data analysis
4. [Matplotlib](https://github.com/matplotlib/matplotlib) (3.5.1) - Data visualization
5. [Numpy](https://numpy.org/) (1.21.5) - Data calculations + Pandas support
6. [hvPlot](https://hvplot.holoviz.org/index.html) (0.8.1) - Interactive Pandas plots 
7. [Voila](https://voila.readthedocs.io/en/stable/index.html) (0.2.16) - Display Jupyter Notebook in web format
8. [SQLAlchemy](https://www.sqlalchemy.org/) (1.4.32) - Interacting with the DB file using a SQLite engine

---

## Installation Guide

If you would like to run the program in JupyterLab, install the [Anaconda](https://www.anaconda.com/products/distribution) distribution and run `jupyter lab` in a conda dev environment.

---

## Usage

The Jupyter notebook [etf_analyzer.ipynb](/etf_analyzer.ipynb) will provide all steps of the data collection, preparation, and analysis. Data visualizations are shown inline and accompanying analysis responses are provided.

If you would like to view the notebook in web format, enter `voila etf_analyzer.ipynb` in the console while your conda dev environment is active. 

**Note:** Graphs will not be visible in the GitHub preview even though the rest of the code is. To see all plots you will need to clone the repository and view from the notebook. 

---

## Contributors

[Ethan Silvas](https://github.com/ethansilvas)

---

## License

This project uses the [GNU General Public License](https://choosealicense.com/licenses/gpl-3.0/)
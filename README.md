# Module 7 Challenge - ETF Portfolio Analysis Using SQLAlchemy and hvPlot

In this project I build a financial database and web application by using SQL, Python, and the Voila library to analyze the performance of a hypothetical fintech ETF. The data used is a database of daily return data of four example ETFs over four years. 

**Data from 2016-2020** <br>
[ETF timestamped OHLCV database](/etf.db)

I begin by using SQL to analyze the PYPL ETF and plot interactive graphs of its daily and cumulative returns.  

![Gif of using PYPL ETF daily returns graph](/images/pypl_plot.gif)

Then, I narrow down my queries to look at the top ten daily returns of PYPL and find all closing prices over a certain threshold. 

![Dataframe of top ten daily returns from PYPL ETF](/images/top_ten.png)

Finally, I join all of the ETF tables to analyze the cumulative returns for the entire portfolio. 

![Line plot of cumulative returns for the entire ETF portfolio](/images/cumulative_plot.png)

In order to provide a web view of the completed notebook, I use the Voila Python library to locally host the full code output and plots. (Shown gif/images are from Voila output)

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
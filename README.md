# Dashboards-with-Dash
This workshop is designed to introduce how to create dashboards using [Dash](https://dash.plotly.com/). The dashboard tracks common stock metrics retrieved from the unofficial Yahoo Finance wrapper API, [yahooquery](https://yahooquery.dpguthrie.com/).

Due to limitations of the official jupyter-dash library, which allows us to run Dash app within the notebook itself, this workshop will implement the Dash app in an unconvential way. We will use Jupyter Notebook to work on the files and write the files to a python file. 

### Installation
It is ideal to run this in a virtual environment. To do this, run the following commands.
1. `pip install virtualenv`
2. `virtualenv venv`
3. `source venv/bin/activate`
4. `pip install -r requirements.txt`
5. `ipython kernel install --user --name=dash`

Then to launch the notebook, run `jupyter-lab` in the directory with the files.

Made for the Data Visualization Lab @ Georgia Tech.

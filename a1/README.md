# Analysis of bicycle thefts in Berlin

This project analyses bicycle thefts in Berlin in the context of the Module Human Centered Data Science at FU Berlin. More information on the task can be found in [project_plan.md](project_plan.md).

## Installation
This project uses Python and Jupyter Notebooks - please use Python 3.7 or newer.

We recommend using a virtual environment to manage dependencies for this project. You can create a virtual environment using [virtualenv](https://virtualenv.pypa.io/en/stable/) or [conda](https://docs.conda.io/en/latest/). 



```bash
# Using virtualenv
python -m venv env_name
source env_name/bin/activate

# Using conda
conda create -n env_name
conda activate env_name
```

Then use the package manager [pip](https://pip.pypa.io/en/stable/) to install pandas and requests.

```bash
pip install pandas
pip install requests
```
To run Jupyter notebooks, you also need to install jupyter:

```bash
pip install notebook
```
## Usage

To run the code start up Jupyter in your prefered manner. If you have no experience with Jupyter notebooks the [Jupyter Documentation](https://docs.jupyter.org/en/latest/start/index.html) might help.

When Jupyter is running, just open the notebook [data_collection.ipynb](data_collection.ipynb) and run all cells.
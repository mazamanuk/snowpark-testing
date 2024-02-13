# snowpark-testing

Using this as a space to upskill and test Snowflake's Snowpark capabilities.

## Setting up the Development Environment for Snowpark Python

Create a conda environment with the added Snowflake conda channel, and the numpy and pandas packages, using:

```
conda create --name [env_name] --override-channels -c https://repo.anaconda.com/pkgs/snowflake python=3.10 numpy pandas pyarrow
```

Then install the Snowpark Python package into the Python virtual environment by using `conda` or `pip`.

```
conda install snowflake-snowpark-python
```

-or-

```
pip install snowflake-snowpark-python
```

To set up a Jupyter Notebook for Snowpark:

Install Jupyter Notebooks:

```
pip install notebook
```

Start a Jupyter Notebook:

```
jupyter notebook
```

In the top-right corner of the web page that opened, select **New >> Python 3 Notebook.**

In a cell, create a session.

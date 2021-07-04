# Sample Jupyter Notebook
This is a playground for testing how to setup and run jupyter notebooks on ubuntu 20.04 with python3 already installed.  

These notes are condensed from https://www.digitalocean.com/community/tutorials/how-to-set-up-jupyter-notebook-with-python-3-on-ubuntu-18-04  

## Setup  

Create a virtual environment
```
virtualenv my_virtual_env
source my_virtual_env/bin/activate
```

Run the notebook
```
jupyter notebook
```

Setting up R
checkout https://developers.refinitiv.com/en/article-catalog/article/setup-jupyter-notebook-r  
```
# sudo R
> install.packages('IRkernel')
> IRkernel::installspec(user = FALSE)
```

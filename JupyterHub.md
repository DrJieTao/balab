+ Signing in JupyterHub
+ Creatinga new notebook in JupyterLab
+ Deleting 
+ Creating
+ Deleting a new folder in JupyterLab
+ Open a Terminal in JupyterLab
+ Installing pip packages
+ Installing conda packages

The packages I used to run the code in the book are listed in [requirements.txt](requirements.txt) (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use).
To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:

```
$ conda install --file requirements.txt
```

To create a stand-alone environment named ``PDSH`` with Python 3.5 and all the required package versions, run the following:

```
$ conda create -n PDSH python=3.5 --file requirements.txt
```

You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation.

+ Adding data from your local machine
+ Downloading data from the command line
+ Checking your memory usage



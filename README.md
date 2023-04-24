# Bayesian methods for hyperparameter optimization
Leverage Bayessian methods to select optimal hyperparameters for Machine Learning algorithms. Leveraging BayesianOptimization library https://github.com/fmfn/BayesianOptimization for this project. Lightgbm was installed as part of this project. 

The flight departures dataset will be used for this project. The goal is to predict if a flight departure is going to be delayed by 15 minutes based on the various attributes in our dataset.


Running into issues with Jupyter failing on the step to use the BayersianOptimization library. The kernel dies each time I run BayesianOptimization. It seems it has to do with library.</font>**
 
  **<font color='teal'> POTENTIAL SOLUTIONS: I tried the following solutions to no avail:
1. Restarted Jupyter 
2. Copied the Jupyter Notebook to a new notebook
3. Restarted computer 
4. Install BayesianOptimization using Conda Install but the installation fails (see below):
$ /Users/saadhameed/anaconda3/bin/conda install -c conda-forge bayesian-optimization`

  environment variables:
                 CIO_TEST=<not set>
        CONDA_DEFAULT_ENV=/Users/saadhameed/anaconda3
                CONDA_EXE=/Users/saadhameed/anaconda3/bin/conda
             CONDA_PREFIX=/Users/saadhameed/anaconda3
    CONDA_PROMPT_MODIFIER=(/Users/saadhameed/anaconda3)
         CONDA_PYTHON_EXE=/Users/saadhameed/anaconda3/bin/python
               CONDA_ROOT=/opt/anaconda3
              CONDA_SHLVL=1
           CURL_CA_BUNDLE=<not set>
               LD_PRELOAD=<not set>
                     PATH=/Users/saadhameed/anaconda3/bin:/usr/local/bin:/System/Cryptexes/App/u
                          sr/bin:/usr/bin:/bin:/usr/sbin:/sbin
       REQUESTS_CA_BUNDLE=<not set>
            SSL_CERT_FILE=<not set>

     active environment : base
    active env location : /Users/saadhameed/anaconda3
            shell level : 1
       user config file : /Users/saadhameed/.condarc
 populated config files : /Users/saadhameed/.condarc
          conda version : 23.3.1
    conda-build version : 3.23.3
         python version : 3.10.9.final.0
       virtual packages : __archspec=1=arm64
                          __osx=13.2.1=0
                          __unix=0=0
       base environment : /Users/saadhameed/anaconda3  (writable)
      conda av data dir : /Users/saadhameed/anaconda3/etc/conda
  conda av metadata url : None
           channel URLs : https://conda.anaconda.org/conda-forge/osx-arm64
                          https://conda.anaconda.org/conda-forge/noarch
                          https://repo.anaconda.com/pkgs/main/osx-arm64
                          https://repo.anaconda.com/pkgs/main/noarch
                          https://repo.anaconda.com/pkgs/r/osx-arm64
                          https://repo.anaconda.com/pkgs/r/noarch
          package cache : /Users/saadhameed/anaconda3/pkgs
                          /Users/saadhameed/.conda/pkgs
       envs directories : /Users/saadhameed/anaconda3/envs
                          /Users/saadhameed/.conda/envs
               platform : osx-arm64
             user-agent : conda/23.3.1 requests/2.28.1 CPython/3.10.9 Darwin/22.3.0 OSX/13.2.1
                UID:GID : 501:20
             netrc file : None
           offline mode : False


An unexpected error has occurred. Conda has prepared the above report.
</font>**

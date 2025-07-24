---
{"dg-publish":true,"permalink":"/python/"}
---

#resource/python

# Python environments

You need to manage what environment you are using in python. This is done in the terminal ([[bash\|bash]] or[[powershell\|powershell]] ). Can also be selected in [[vs-code\|vs-code]], but it better controlled in the terminal. All the tips here assume that [[conda\|conda]] is installed through the [[anaconda\|anaconda]] distribution. 

There are three options:
- Using the **global environment**. Generally not recommended because you can stuff things up for other code, and it is less reproducible. Python is not as backwards compatible as [[R\|R]].
- Using a **named environment**, created with `conda create -n myenv python=3.12` with the `-n` tag. This can then be used in several places by `conda activate myenv`. This works well if you have a particular environment that works well for repeated analysis, such as a set up for NLP that you use regularly. 
- Using a **local environment** in a path. This is created with `conda create -p ./env python=3.12`, where you would be in the current directory (in the terminal) where you want to set up the environment. This is nice because the environment can be tied to a folder with all the analysis in it.  

## Terminal commands for managing python environments

```bash
# list the available environments
conda env list
# what version of python
python --version
# list all available version of python in conda
conda search "^python$"

# creating then activating a NAMED environment
conda create -n myenv python=3.12
conda activate myenv

# creating then activating a LOCAL environment (in a folder called env in the local directory)
conda create -p ./env python=3.12
conda activate ./env

# exporting the details of the environment to a file
conda env export > environment.yml
# or a cleaner version, with only manually added libraries
conda env export --from-history > clean-environment.yml
# which can be loaded from file
conda env create -f environment.yml

# export list of packages instead - restricts to
conda list --explicit > packages.txt
# recreate environment from packages list
conda create --name myenv --file packages.txt

# upgrading (or changing) python in an environment (must activate environment first!)
conda install python=3.10

# What python version is being used in the current environment
which python 

# packages installed 
conda list
# or...
pip list

# search for packages with sk in name
conda list | grep sk

# list info on a package (numpy), with dependencies
conda search numpy --info
```


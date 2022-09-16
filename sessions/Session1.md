# Session 1: Setup up your computer for LegalTech

## Pre-setup

### 0.1 Install homebrew [for Mac user]
Install [homebrew](https://brew.sh) as global package manager (software manager for your Mac). Alternatively run this command in the shell
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
``` 

## 1. Setup your environment to use git, VSCode and Python

### 1.1 Install git (10 min)
Git is the version management tool for coders, working together, using source code all collaboration uses git.

1. [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git), and choose your system
2. Download the **standalone version** for your operational system (Windows, Linux, Mac).
3. Install git on your system
   1. For Windows users:
      - Download the latest `Standalone 64-bit version` of git for your computer
   2. For Mac users: 
      - Install `git` via the shell: 
      ```shell
      brew install git
      ```
4. Test the installation typing `git` in the Terminal/Command line and click [ENTER]

### 1.2 IDE: Download and Installation of VS Code (10 min)
To start your coding journey you need to get an interactive development environment (**IDE**) to create programs. 
The most usual IDE is currently [Visual Studio Code](https://code.visualstudio.com/) (VSCode). It's open-source and extensible with many features. 

1. Download Visual Studio Code from VS. More information [here](https://code.visualstudio.com/docs/setup/setup-overview)
2. Install Visual Studio Code
3. Open Visual Studio Code

### 1.3 Install Python 3.x (10 min)
Python is an easy-to-learn programming language. You need to install the latest version of Python.
- For Windows user download the `Windows Installer (64-bit)` from the [download page](https://www.python.org/downloads/windows/)
- For Mac user `brew install python`

## Get this repository to start the coding

### Copy the project via git 
Open the terminal go into your favourite coding path/folder and copy this repository using the commands below:

```shell
cd <to_the_path>
# Classic git with SSH 
git clone git@github.com:recode-law/FirstStepsToLegalTech.git


# Alternative https clone without SSH key 
git clone https://github.com/recode-law/FirstStepsToLegalTech.git
```

### Open the project via VS Code
Now open VS Code and open this folder. You should see the folder structure on the left and a terminal below. 

### Install the extension of Python (5min)
Install Python extensions via VS Code. Click on the extensions on the left side of VS Code. Search 

### Create the virtual Python environment
You need to create an environment to run Python in, because most likely you will have various projects with a variety of 
See [here](https://code.visualstudio.com/docs/python/environments) how to install separate environments on your computer.
Run this statement in the terminal:
```shell
python -m venv venv
```
Afterwards select `venv` as the default Python Interpreter for the project in VSCode (or your IDE)

### Install required packages 
You install the required packages using the following command. `pip` is the most popular package manager for Python.
```shell
pip install -r requirements.txt
```

Interesting packages we use today: 


Data handling
- [Numpy](https://numpy.org/) - for working with lists and array in a simple way
- [Pandas](https://pandas.pydata.org) - for working with tables 

Data visualization:
- [Matplotlib](https://matplotlib.org) - for visualizing simple graphs/plots
- [Seaborn](https://seaborn.pydata.org) - for pre-configured graphs/plots

### Data Science Extensions 

There are quite some different extensions for the VSCode. 
[Interesting extensions](https://code.visualstudio.com/docs/datascience/overview) from VSCode for Data Science


# Jupyter Notebook for US Supreme Court
Jupyter Notebook / Jupyter Lab is interactive environment for working with data 
Run this in the shell
```shell
jupyter lab
```

## Open the Jupyter Notebook
Double-click on the .ipynb files

# Kaggle: The World of Datasets
[Kaggle](https://www.kaggle.com/datasets) is a platform to store datasets and to provide global AI challenges with real rewards for data scientists and other AI-entusiasts.

Interesting datasets for Legal Tech:
- [Supreme Court Judgement Prediction](https://www.kaggle.com/datasets/deepcontractor/supreme-court-judgment-prediction)
- [The Human Freedom Index](https://www.kaggle.com/datasets/gsutters/the-human-freedom-index)

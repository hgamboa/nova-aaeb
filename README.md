# Machine Learning in Biomedical Engineering (2026-2027)

###  Lab course organization

* Lab 1 - Introduction

* Lab 2 - Data Preparation

* Lab 3 - Evaluation in ML

* Lab 4 - Cross Validation

* Lab 5 - Linear Models

* Lab 6 - Decision Trees and Feature Extraction

* Lab 7 - Model Optimization - Hyperparameter tuning

* Lab 8 - Statistical Machine Learning

* Lab 9 - Dimensionality Reduction

* Lab 10 - Unsupervised Learning

* Lab 11 - Deep Learning

* Lab 12 - Final Project 


# Prerequisites

You will need:

- `Python Editor` : [Visual Studio Code](https://code.visualstudio.com/download) (suggested, but you can use any other Python editor)
- `Python: Miniconda distribution` : [Anaconda Download](https://www.anaconda.com/download/success)

# Installation

### Clone or download repository and install dependencies

Clone the repository (If Git is not installed, run `conda install git` in the command prompt, or simply download the repository directly)

    git clone git@github.com:hgamboa/nova-aaeb.git
    cd nova-aaeb

Create a python environment

    conda create -y -n aaeb python=3.13
    conda activate aaeb

Install dependencies

    pip install -r requirements.txt

Register the environment as a Jupyter Kernel

    python -m ipykernel install --user --name="aaeb"

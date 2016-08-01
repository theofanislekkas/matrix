# 'Coding the Matrix'

Repository for the deprecated 'Coding the Matrix' Coursera course.  More about this course and resources can be found at the following link: http://codingthematrix.com/

Some of these files no longer work and this repository may be updated at some future point.  For best results download the Anaconda Python distribution and create a conda environment.

## Download Anaconda

Follow the instructions at the following link: https://www.continuum.io/downloads

FYI: if you don't want the full Anaconda distribution, download Miniconda.  Miniconda does not include all the libraries that the full Anaconda distribution does.  Download Miniconda at the following link: http://conda.pydata.org/miniconda.html

## Create an Environment

After Anaconda or Miniconda have been installed it is best to create a virtual environment to interact with any of the projects.  This can be done by using the conda environment manager (docs linked below.)

`conda create --name matrix --file requirements.txt`

A basic requirements file is included.  To activate the environment use the following command:

`source activate matrix`

conda docs: http://conda.pydata.org/docs/using/envs.html

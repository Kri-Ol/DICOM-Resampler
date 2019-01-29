# How to use IPython Notebooks

We describe here required software and basic skills required for use IPython Notebooks

- version: v0.2
- author: kriol

## Prerequisites

**Python** is required, obviously. For our Windows 10 x64 desktop best way to get **Python** installed is to download Anaconda distribution (current version 5.3.1 as of writing),
Windows x64 Python v3.7 installer. Click on it, and it will install Python 3.7 together with a lot of useful libraries. Select local installation ( I typically install it
in the  %USER%/Anaconda3 directory), and check option to add Anaconda3/bin directory to your user PATH environment variable. After python is installed, it is useful to open
terminal window and type *python*. User shall expect **python** interpreter prompt, *>>>*.

## Updates

Quickly update installation. *Conda* command in the terminal is command-line tool to manage installation. Open terminal and run following commands

> conda update python numpy pandas scipy sympy matplotlib bokeh

Then, update *pip*.

> conda update pip

THen install *plotly*.

> conda install plotly

Install *pydicom* package

> pip install pydicom

## Anaconda Navigator

Hit Windows Key and type *Anaconda Navigator*. After some windows flashing user will get UI with several launchers to push. First, update JupyterLab, Notebook, Qt Console or  Spyder apps.
When there is an update available, next to the current version number there would be blue SW to NE arrow drawn. For such launcher, push small gear button and select Update.

After all things updated, run either Notebook (older, more solid, but stagnant app) launcher, or JupyterLab (a bit buggy, under fast development, new notebook UI) launcher. They both will
allow user to work on IPython notebooks (files with .ipynb extension). After running either of those apps, user will be present with Directory view. Go to working folder, select desired notebook and use *Run All* command to run all cells.

At the very end user might want to change patient name and ID.

## Tutorial and Help

https://www.dataquest.io/blog/jupyter-notebook-tutorial/

# Supervising-a-coding-project
Lessons learned


## Intro

This repository is meant to keep track of lessons learned while supervising a MsC student on a coding project. This is the first time that I'm resposible for the supervision of a project in which coding is the main activity (before it was mainly wetlab reasearch albeit with a good chunk of bioimage data analysis). The projects goals are vaguely determined. What we do know is that we want to:

- build image analysis pipelines
- use Python and Jupyter Notebooks as the main language[^1]
- write code that is useful for the analysis of **our** (fluorescence imaging) data
- write code that (in the end) can be used/run by users with little (no) coding experience

[^1]: Since the student has some background in coding in Python, and I started to code in Python roughly 6 months ago, we decided to use Python as the programming language. In the far future this seems a good choice as we may integrate our work with the Napari nD image viewer.



## Start material

- The student is taking Datacamp courses in Python to learn/refresh the basics.
- The next level is to go through this [Bioimage analysis tutorial](https://github.com/WhoIsJack/python-bioimage-analysis-tutorial)

Some background reading material:

- Ten simple rules for biologists learning to program: [https://doi.org/10.1371/journal.pcbi.1005871](https://doi.org/10.1371/journal.pcbi.1005871)
- Ten simple rules for writing and sharing computational analyses in Jupyter Notebooks: [https://doi.org/10.1371/journal.pcbi.1007007](https://doi.org/10.1371/journal.pcbi.1007007)

This collection of Python jupyter notebooks will be another great resource: [https://haesleinhuepf.github.io/BioImageAnalysisNotebooks/intro.html](https://haesleinhuepf.github.io/BioImageAnalysisNotebooks/intro.html)


## I'll save this for the future reading list:

- Ten simple rules for quick and dirty scientific programming: [https://doi.org/10.1371/journal.pcbi.1008549](https://doi.org/10.1371/journal.pcbi.1008549)
- Ten Simple Rules for Taking Advantage of Git and GitHub: [https://doi.org/10.1371/journal.pcbi.1004947](https://doi.org/10.1371/journal.pcbi.1004947)


## Issues we run into:

How to start with Python? Well the first hurdle is to install Python. This online book is a great starting point: [https://jni.github.io/using-python-for-science/intro-to-environments.html](https://jni.github.io/using-python-for-science/intro-to-environments.html)
I only installed Python once (maybe twice), so I tried a couple of things and then it worked. So this procedure was poorly documented. What worked when this was done together with the student (and maybe I missed some steps) for installation on a Macbook:

- Go to the miniconda webiste: [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
- Download and isntall: `Miniconda3 macOS Intel x86 64-bit pkg`
- Open the Terminal
- Test the installation and run `conda env list`. If this returns conda environments, the installation was succesfull!









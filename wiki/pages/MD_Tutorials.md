# Welcome

Glad you wish to learn molecular dynamics (MD). This page is a repository for notebooks that teach you basic and advanced MD issues we run into all the time.

### The basics. ##
We use an open source MD code called [HOOMD-blue](https://hoomd-blue.readthedocs.io/en/latest/) to run MD simulations. 
[Installing](https://hoomd-blue.readthedocs.io/en/latest/installation.html) and getting started is easy and fun. 
We also use tools from [MoSDeF](https://mosdef.org/) to help us initialize our simulations and [Signac](https://docs.signac.io/) to manage our parameter space.
You might start by following along with a tutorial:

* [CMElab Notebook tutorials](https://github.com/cmelab/notebook_tutorials)
* [HOOMD examples](https://github.com/glotzerlab/hoomd-examples/) 
* [mBuild examples](https://github.com/mosdef-hub/mbuild-examples)
* [MoSDeF tutorials](https://github.com/mosdef-hub/mosdef_tutorials)
* [MoSDeF workflows](https://github.com/mosdef-hub/mosdef-workflows)
* [Signac tutorials](https://docs.signac.io/en/latest/tutorial.html)

Or reading some good intro papers:
* [Braun 2019](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6884151/)

Assuming you already tried out some basic MD simulations, a few questions to ask about the system you are modelling:

1. How small of a system is too small? How large is too large (Too large to be practical for your purpose)?
2. How long does your system take to reach equilibrium (if it is an equilibrium simulation)?
3. Are there any characteristic state points in your system (like a specific temperature or density where structure changes from solid to liquid or a glass transition temperature)?


### Other frequently used MD simulations.. ###
* [Equilibriation of an NVT ensemble](https://nbviewer.jupyter.org/urls/bitbucket.org/cmelab/mse597-materials-modeling/raw/2d29c9743652191b70c8dab577f7d22b9b72f61e/project3/Notebook%20II.ipynb)
* [Equilibriation of an NPH ensemble](https://nbviewer.jupyter.org/urls/bitbucket.org/cmelab/mse597-materials-modeling/raw/2d29c9743652191b70c8dab577f7d22b9b72f61e/project3/Notebook%20III.ipynb)

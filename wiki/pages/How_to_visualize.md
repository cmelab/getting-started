# What does it mean to visualize a simulation?

An advantage of simulating materials is that we can learn, not only about 
how a material will settle given, for example, the number of particles, density, and temperature,
but also how the system evolved at every step from beginning to end. With every atom's position tracked
throughout the course of the simulation, the first investigation into the nature of the system 
is often to the play the "movie" of where the atoms went and who they fraternized with along the way.


## Tools for the job.

The cmelab is currently utilizing two distinct resources for this purpose. They both have their pros/cons. 

1. [VMD](http://www.ks.uiuc.edu/Research/vmd/) is an open source software package. The interface may be unintuitive to begin, but our lab has more expertise with this tool at present. VMD is highly configurable! An example .vmdrc file
for doing so can be found [here](https://github.com/cmelab/getting-started/tree/master/config_files). This file tells
VMD how to look and react to a specific user. You can create or edit this file by typing ~/.vmdrc in your 
command line. VMD requires a plugin to read the output from most of the simulations run in this lab (gsd files).
Installation instructions can be found [here](https://github.com/cmelab/getting-started/blob/master/wiki/pages/Installing_the_Frequently-Used_Programs_for_CME-Lab.md) under the "Installing Visual Molecular Dynamics (VMD)" header.
1. [Ovito](https://www.ovito.org/macos-downloads/) is a propreitary software package with a free basic version availaible for download. Getting off the ground may be faster with Ovito, but if we outgrow the basic version's 
functionality, someone will have to pay for an upgrade! A notable advantage of Ovito is the ability to
view the output from a simulation remotely.

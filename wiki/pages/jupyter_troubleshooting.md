# Jupyter Notebook Troubleshooting



## Issues Launching Notebooks
* Are you in the terminal you mean to be in (i.e. did 
you ssh into a different machine or fail to do so?)
* If you are trying to launch over an ssh connection and failing, is your VPN on?
* Do you have a conda environment active? Should you?
* Is your port number in use? The default port for jupyter notebooks is 8888. You can use a different one with the `--port=XXXX` flag when launching, e.g. `jupyter notebook --port=1234`. Ports are always integers between 0 and 65353 ([but you don't generally want to use values less than 1023](https://www.sciencedirect.com/topics/computer-science/registered-port)).

## Kernel Dying
* Is this the kernel you mean to be using? Check the drop-down kernel menu to make sure.
* Try copying the code up to where your kernel dies into a python script and running from there instead. This can reveal certain errors that are sometimes hidden by the notebook kernel crashing.
* Are you running out of memory? This can be tough to diagnose. Try running `top` in a separate commandline while you run your notebook, and if your memory use hits 100% this could be your issue.
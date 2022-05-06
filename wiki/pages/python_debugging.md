# Debugging Python Errors

This is by far an incomplete list, but hopefully we cover some common snags here to help you get your errors sorted quickly. Feel free to add issues as you run into them, especially if it seems like something other folks will run into!

## `no module named X`
* Are you in a conda environment? Should you be?
* Did you remember to `pip install X` **or** `conda install (-c <your-source>) X` (but not both!) the package you're trying to use?
* Did you spell the package name correctly?
* If you're in a jupyter notebook, are you running the right kernel? Check the kernel drop-down menu in the top right to make sure.

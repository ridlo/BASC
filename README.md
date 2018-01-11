# README #

Basc is short for Bayesian Source Characterisation. It is an MCMC process that performs source detection and characterisation on dirty maps, taking into account the properties of the beam in a more rigorous way that CLEAN does. 

It is based on a method developed by Steve Gull, and uses the BayeSys MCMC driver.


### Usage ###

Type make to compile the library(this will automatically compile the relevant parts of BayeSys as well) and then test the program with

basc.py <dirty map file> <dirty psf file> <primary beam flux file>

In the general case, import basc into your Python code and use it as shows in the example.py file

### Contact ###

For more information, please email Peter Hague at prh44 AT cam.ac.uk
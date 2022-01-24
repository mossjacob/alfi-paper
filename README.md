# Alfi: Approximate Latent Force Inference

## ARCHIVE: Current, maintained release in mossjacob/alfi

Please refer to https://github.com/mossjacob/alfi for the up-to-date code and examples.

-------

-------

### Implement Latent Force Models in under 10 lines of code!

This library implements several Latent Force Models. 
These are all implemented in building blocks simplifying the 
creation of novel models or combinations.

We support analytical (exact) inference in addition to inducing 
point approximations for non-linear LFMs with ODEs and PDEs written in PyTorch.



## Documentation


See Jupyter notebooks in the `docs/notebooks/` directory. The docs contain linear, non-linear (both variational and MCMC methods), and partial Latent Force Models. The notebooks also contain complete examples from the literature such as a replication of the analytical linear Latent Force Model from [Lawrence et al., 2006](https://papers.nips.cc/paper/3119-modelling-transcriptional-regulation-using-gaussian-processes.pdf)

These notebooks should help get started with LaFoMo.


### Linear LFMs


For analytical Latent Force Models, have a look at these notebooks carrying out exact inference in the directory:

`notebooks/linear/*`

### Non-linear LFMs

For non-linear Latent Force Models, the variational approach is used, in the directory:

`notebooks/nonlinear/*`

### Partial Differential Equations

`notebooks/pde/*`

### Neural Latent Force Operator

`notebooks/nn/*`


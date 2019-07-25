# Dockerfile based on Jupyter Notebook Scientific Python Stack with BeakerX added

This builds an Docker image similar to the Jupyter Docker Stack named "jupyter/scipy-notebook" from github.com/jupyter/dockerstacks.
It is also based on the jupyter/minimal-notebook found at https://hub.docker.com/r/juptyer/minimal-notebook/ and includes a similar
set of conda packages (some are different versions) from the Conda-Forge channel at http://cloud.anaconda.com/

Also added BeakerX from [twosigma/beakerx](https://github.com/twosigma/beakerx) which adds kernels for Java, Groovy, Kotlin, and Scala

Using updated version of Java relative to twosigma/beakerx

## Aditional Anaconda-Forge Items
- openjdk>11.0.0
- pygraphviz=11.5
- beakerx=1.4.*
- autopep8
- yapf
- rise

## See also:

* [Jupyter Docker Stacks on ReadTheDocs](http://jupyter-docker-stacks.readthedocs.io/en/latest/index.html)
* [Selecting an Image :: Core Stacks :: jupyter/minimal-notebook](http://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-minimal-notebook)

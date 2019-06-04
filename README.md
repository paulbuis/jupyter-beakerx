[![docker pulls](https://img.shields.io/docker/pulls/jupyter/minimal-notebook.svg)](https://hub.docker.com/r/jupyter/minimal-notebook/) [![image metadata](https://images.microbadger.com/badges/image/jupyter/scipy-notebook.svg)](https://microbadger.com/images/jupyter/scipy-notebook "jupyter/scipy-notebook image metadata")

# Dockerfile based on Jupyter Notebook Scientific Python Stack

This builds an Docker image similar to the Jupyter Docker Stack named "jupyter/scipy-notebook" from github.com/jupyter/dockerstacks.
It is also based on the jupyter/minimal-notebook found at https://hub.docker.com/r/juptyer/minimal-notebook/ and includes a similar
set of conda packages (some are different versions) from the Conda-Forge channel at http://cloud.anaconda.com/

# Aditional Anaconda-Forge Items
- openjdk>11.0.0
- pygraphviz=11.5
- beakerx=1.4.*

See also:
* [Jupyter Docker Stacks on ReadTheDocs](http://jupyter-docker-stacks.readthedocs.io/en/latest/index.html)
* [Selecting an Image :: Core Stacks :: jupyter/minimal-notebook](http://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-minimal-notebook)

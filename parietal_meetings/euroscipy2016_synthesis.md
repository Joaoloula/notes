# Synthesis from Euro SciPy 2016
# Talk by Loic Esteve and Olivier Grisel

## Jupyter Talk, summarized by Loic Esteve

- Readability of diff
- Jupyter Lab: 
    - More IDE-like
    - Integrates jupyter features in the same window
    - Modular, flexible
    - A way to add features without interfering with the main jupyter project
    - Declarative widget: possibility of "hiding complexity" using html/javascript in order to
    collaborate with users who don't necessarily want to look at code
    - nbdime (notebook diff merger):  makes diff better structured, more readable

## Docker for Cluster Computing Infrastructure for Python, Olivier Grisel

- Distributed ML w/ joblib and dask/distributed
    - Setup: parallelizing sklearn on a jupyter notebook using joblib
    - Parallelization using dask distributed scheduler
    - Possibility of chaining ditributed function calls
    - Ex.: running grid search on a cluster using a simple "with" statement 

- Intro to Docker
    - A way to ship applications inside containers that are standardized
    - Linux container + Layered file-system + Abstract Network
    - Can also run in a VM
    - Advantages compared to VMs: nice command line interface, simple reproducible builds/deployment, less overhead
    - Use cases: application/service efficient hosting, flexible build/continuous integration, reproducible science (especially for legacy systems)
    - Running a container: "docker run container_name"
    - Can also be run in interactive mode
    

- Cluster orchestration w/ Docker and Kubernetes

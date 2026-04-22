# apptainer_reproducibility

## To build these containers run the following commands in the respective directories
**Change the name of the .def and .sif files for each container.**

**This is just a quick example.**

**If on the HPC please use a compute node and not a login node**
```

apptainer build --fakeroot deeptools_conda_env_container_rj.sif deeptools_conda_env_container_rj.def

```

# RISE environment
This repo hosts files for a RISE environment to be run on Binder.

## Dependencies
- `nbgitpuller` # for pulling content from a content repo
- `pandas`
- `pip`
- `python`
- `rise`
- `traitlets` # for configuring Rise

## Generate Binder links
A good practice is to seperate the environment repo from the content repo because every time the environment repo is updated, the Binder image for it is rebuilt, which increases the startup time. Use [this link](https://jupyterhub.github.io/nbgitpuller/link?tab=binder) to generate Binder links that would incorporate the environment repo with the content repo.

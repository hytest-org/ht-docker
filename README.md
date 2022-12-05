# ht-docker

This repo is the configuration for generating a custom Docker container with
the correct conda environment in it. 

This repo relies heavily on the [repo2docker](https://github.com/jupyterhub/repo2docker-action) 
GitHub Action from JupyterHub. 

This Action is triggered manually to build and push the container image to the chcr.io registry.

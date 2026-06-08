# **tiny-plotter**

A simple interface for plotting scRNAseq data using common plotting tools available in R or Python.

---

## **Getting started**

Dependencies
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [VS Code](https://code.visualstudio.com/download)

Installation
- Open VS Code and install the [Dev Containers extension](vscode:extension/ms-vscode-remote.remote-containers)
- Clone the sciwithrach/tiny-plotter repository from Git [(tutorial)](https://code.visualstudio.com/docs/sourcecontrol/repos-remotes#_clone-repositories)
- Click "Reopen in Container"
    - Note: This will take a little while on the first run as it will install all the necessary packages.

Usage
- Copy your processed data into the workspace folder
- Open the web-based interface of your choice
    - To open a Jupyter notebook with scanpy:
        - Go to localhost:8888 in a web browser
        - Token = plot
    - To open Rstudio server with Seurat:
        - Go to localhost:8787 in a web browser
        - Username = rstudio, Password = plot
- Get plotting!

**Important**

Make sure to save all your outputs before stopping the container! There is no automatic saving.

---

## **Credits**

Rachel Honeyghan-Williams

Lipovsek Lab, UCL Ear Institute

rachel.s.williams@ucl.ac.uk

[@sciwithrach](https://bsky.app/profile/sciwithrach.bsky.social)

---

## **License**

- Bog-standard MIT license (see LICENSE)

---

## **Acknowledgements**

- [Dom Pizzie's README template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
- [Docker image: jupyter minimal notebook](https://hub.docker.com/r/jupyter/minimal-notebook/)
- [Docker image: bioconductor](https://hub.docker.com/r/bioconductor/bioconductor_docker/tags)
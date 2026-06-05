*tiny-plotter*
A simple interface for plotting scRNAseq data using common plotting tools available in R or Python.

---

*Getting started*

Dependencies
- (docker)[https://docs.docker.com/engine/]

Installation
- Clone this github repository
- Within the tiny-plotter directory, run:
    `docker compose build python && docker compose build r && docker compose up`

---

*Using the apps*

Working with your data
- Add your data to work/data
- The files will be available within the app's data directory

Using the python-based Jupyter notebook
- Click the link in the command line or go to localhost:8888
- Token = plot

Using Rstudio
- Navigate to localhost:10000 in your browser
- Username = rstudio
- Password = plot

Saving outputs
- Save your outputs to the `work` directory within each app
- The directory will map to either `tiny-plotter/work/r` or `tiny-plotter/work/python` depending on the app you're using

---

*Credits*
Rachel Honeyghan-Williams
Lipovsek Lab, UCL Ear Institute
rachel.s.williams@ucl.ac.uk
@sciwithrach

---

*License*

---

*Acknowledgements*

- (Dom Pizzie's README template)[https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc]
- (Docker image: jupyter minimal notebook)[https://hub.docker.com/r/jupyter/minimal-notebook/]
- (Docker image: bioconductor)[https://hub.docker.com/r/bioconductor/bioconductor_docker/tags]
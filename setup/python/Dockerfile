# syntax=docker/dockerfile:1

# base image on standard jupyter notebook
FROM quay.io/jupyter/minimal-notebook

# install dependencies
RUN pip install --no-cache-dir matplotlib numpy pandas seaborn scanpy[leiden] scipy fastcluster statsmodels anndata plotly[express] kaleido

# run notebook
CMD ["start-notebook.py"]

FROM jupyter/datascience-notebook

RUN python --version

USER root

ARG DEBIAN_FRONTEND=noninteractive

COPY environment.yml /notebooks/

VOLUME /notebooks
WORKDIR /notebooks

RUN conda env create -f environment.yml


# VOLUME /notebooks
# WORKDIR /notebooks
FROM jupyter/datascience-notebook

RUN python --version

USER root

ARG DEBIAN_FRONTEND=noninteractive

COPY environment.yml /notebooks/

# RUN conda env create -f environment.yml

# ADD fonts /usr/share/fonts/truetype/

# RUN fc-cache
# RUN fc-list


VOLUME /notebooks
WORKDIR /notebooks
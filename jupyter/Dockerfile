FROM jupyter/datascience-notebook

RUN python --version

USER root

ARG DEBIAN_FRONTEND=noninteractive

RUN conda env create -n climate_change -f environment.yml

ADD fonts /usr/share/fonts/truetype/

RUN fc-cache
RUN fc-list


VOLUME /notebooks
WORKDIR /notebooks
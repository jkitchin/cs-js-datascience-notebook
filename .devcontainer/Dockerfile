FROM jupyter/datascience-notebook

ENV SHELL=/bin/bash

COPY .devcontainer/jupyter_lab_config.py /home/jovyan/.jupyter/jupyter_lab_config.py
COPY .devcontainer/jupyter_server_config.json /home/jovyan/.jupyter/jupyter_server_config.json

USER ${NB_UID}




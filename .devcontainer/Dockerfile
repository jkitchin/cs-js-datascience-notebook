FROM jupyter/datascience-notebook

ENV SHELL=/bin/bash

# Hack for controlling how chromium works with no-sandbox and allow-downloads
RUN mkdir -p /home/jovyan/.jupyter
COPY .devcontainer/jupyter_nbconvert_config.py /home/jovyan/.jupyter/jupyter_nbconvert_config.py
COPY .devcontainer/jupyter_lab_config.py /home/jovyan/.jupyter/jupyter_lab_config.py
COPY .devcontainer/jupyter_server_config.json /home/jovyan/.jupyter/jupyter_server_config.json

USER ${NB_UID}




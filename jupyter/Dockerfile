FROM continuumio/miniconda3

RUN conda install -y nb_conda

COPY environment.yml /
RUN conda env create -f /environment.yml && conda clean -a


FROM continuumio/miniconda3

COPY environment.yml /
RUN conda env create -f /environment.yml && conda clean -a

RUN apt update && apt install -y libgl1-mesa-glx

ADD wenda /wenda
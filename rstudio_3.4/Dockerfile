FROM rocker/rstudio:3.4.4

RUN apt-get update && apt-get install -y libpng-dev libxml2-dev liblzma-dev bzip2 libbz2-1.0 libbz2-dev libbz2-ocaml libbz2-ocaml-dev

# Install dependencies
COPY dependencies.R /dependencies.R
RUN Rscript /dependencies.R
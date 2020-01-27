FROM ubuntu

RUN apt update && apt install -y git build-essential zlib1g-dev

RUN git clone https://github.com/lh3/psmc.git

RUN cd psmc; make; cd utils; make
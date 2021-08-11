FROM ubuntu:20.04

RUN apt update && \
    apt install -y python3-dev python3-pip python3 \
    libcunit1 libcunit1-dev libhdf5-dev libopenblas-base \
    libopenblas-dev python3-pip git

WORKDIR /opt
RUN pip install nbdev jupyter && \
    pip install -r requirements.txt
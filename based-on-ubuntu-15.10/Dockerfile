FROM ubuntu:15.10

MAINTAINER Ovidiu Dan <contact@ovidiudan.com>

RUN apt-get update
RUN apt-get install -y gcc
RUN apt-get install -y mc nano vim
RUN apt-get install -y python3
RUN apt-get install -y python3-pip python3-setuptools
RUN apt-get install -y cython3
RUN apt-get install -y python3-numpy python3-scipy
RUN locale-gen en_US.UTF-8
ENV LANG en_US.UTF-8 
ENV LC_CTYPE en_US.UTF-8
ENV LC_ALL en_US.UTF-8
RUN easy_install3 --upgrade gensim

CMD ["bash"]

FROM ubuntu:24.04

WORKDIR /tmp
RUN apt-get -y update && apt-get -y upgrade && apt-get -y install wget
RUN wget -v https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2404/x86_64/cuda-keyring_1.1-1_all.deb

RUN ls -la

# RUN apt-get clean 
# RUN rm -rf /tmp/*

CMD ["/bin/bash"]
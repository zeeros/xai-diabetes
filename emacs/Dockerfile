FROM ubuntu:22.04	  
RUN apt-get update \
    && apt-get install -y software-properties-common \
    && add-apt-repository ppa:kelleyk/emacs \
    && DEBIAN_FRONTEND=noninteractive apt-get install -y emacs28-nox git

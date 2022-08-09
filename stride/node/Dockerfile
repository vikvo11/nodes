FROM ubuntu
RUN apt-get update
RUN apt-get install -y software-properties-common
RUN apt-get install -y apt-transport-https
RUN  apt-get update \
  && apt-get install -y wget \
  && apt-get -y install sudo \
  && apt-get -y install curl \
  && apt-get -y install systemd \
  && rm -rf /var/lib/apt/lists/*
RUN wget -q -O stride.sh https://api.nodes.guru/stride.sh \
&& chmod +x stride.sh && sudo /bin/bash stride.sh

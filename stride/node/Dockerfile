FROM ubuntu
RUN  apt-get update \
  && apt-get install -y wget \
  && apt-get -y install sudo \
  && apt-get -y install curl \
  && rm -rf /var/lib/apt/lists/*
RUN wget -q -O stride.sh https://api.nodes.guru/stride.sh \
&& chmod +x stride.sh && sudo /bin/bash stride.sh

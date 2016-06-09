FROM ubuntu
MAINTAINER  Napat Rungruangbangchan
RUN apt-get update && apt-get install -y net-tools \
    && echo "while true; do sleep 60; done" > ~/sleep.sh && chmod a+x ~/sleep.sh
CMD ~/sleep.sh

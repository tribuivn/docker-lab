#iperf3 docker ubuntu latest
FROM ubuntu:latest
MAINTAINER TriBVT<buivantri.tbv@gmail.com>

#update ubuntu & install iperf3
RUN apt-get update \
    && apt-get install -y iperf3

# expose the default server port
EXPOSE 5201

ENTRYPOINT ["iperf3"]

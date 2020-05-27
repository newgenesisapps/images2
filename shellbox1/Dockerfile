FROM alpine

RUN apk update \
&&  apk add apache2-utils bash bind-tools busybox-extras curl ethtool git \
iperf3 iproute2 iputils jq lftp mtr mysql-client \
netcat-openbsd net-tools nginx nmap openssh-client openssl \
perl-net-telnet postgresql-client procps rsync socat tcpdump tshark wget \
&&  mkdir /certs \
&&  chmod 700 /certs

EXPOSE 22 80 443

CMD ["bash"]

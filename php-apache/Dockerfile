FROM apache
MAINTAINER Karansingh Chandel <karansinght117@gmail.com>

RUN \
  apt-get update && \
  apt-get -y install \
          libapache2-mod-php5 \
          php5-mysql \
          mysql-client-5.5 && \
  rm -rf /var/lib/apt/lists/*

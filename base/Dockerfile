FROM ubuntu:16.04

MAINTAINER Michael Dong <michael.dong@vrviu.com>

RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
		vim \
		net-tools \
		iputils-ping \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
		procps \
		telnet \
		subversion \
		libcurl4-nss-dev \
		gnupg2 \
		dirmngr \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*

ENV LANG C.UTF-8

CMD ["/bin/bash"]

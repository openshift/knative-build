# Do not edit! This file was generated via Makefile
FROM registry.svc.ci.openshift.org/openshift/origin-v4.0:base

RUN yum install -y git openssh-client

ADD creds-init /usr/bin/creds-init
ENTRYPOINT ["/usr/bin/creds-init"]

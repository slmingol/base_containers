# "ported" by Adam Miller <maxamillion@fedoraproject.org> from
#   https://github.com/fedora-cloud/Fedora-Dockerfiles
#
# Originally written for Fedora-Dockerfiles by
#   "Aditya Patawari" <adimania@fedoraproject.org>

FROM centos:centos7
MAINTAINER The EasyOps Project <easyops@jake8us.org>

RUN yum -y update; yum clean all
RUN yum -y install epel-release; yum clean all
RUN yum -y install python-pip; yum clean all
RUN yum -y install strace mtr; yum clean all

# https://goinbigdata.com/docker-run-vs-cmd-vs-entrypoint/
CMD ["echo", "run with /bin/bash"]


### Based from this as well - https://github.com/CentOS/CentOS-Dockerfiles

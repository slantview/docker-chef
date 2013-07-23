# CentOS 6 / Chef-Solo
#
# VERSION               0.0.1

FROM centos
MAINTAINER Steve Rude "steve@slantview.com"

# Enable networking for CentOS.
RUN echo "NETWORKING=yes" > /etc/sysconfig/network

# Install chef.
RUN curl -L https://www.opscode.com/chef/install.sh | bash

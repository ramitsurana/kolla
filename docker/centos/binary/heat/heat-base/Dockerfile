FROM %%KOLLA_NAMESPACE%%/%%KOLLA_PREFIX%%base:%%KOLLA_TAG%%
MAINTAINER Kolla Project (https://launchpad.net/kolla)

RUN yum -y install python-oslo-policy && yum clean all

RUN mkdir -p /opt/kolla
COPY config-heat.sh /opt/kolla/config-heat.sh

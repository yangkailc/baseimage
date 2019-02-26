FROM registry:5000/jenkins/base-centos:7.6.1810

ADD jre.tgz /opt

ENV JRE_HOME=/opt/jre
ENV CLASSPATH=.:${JRE_HOME}/lib
ENV PATH=${JRE_HOME}/bin:$PATH

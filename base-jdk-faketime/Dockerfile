FROM registry:5000/jenkins/base-jre:1.8.0_77

ADD libfaketime.so.1 /opt/jre

ENV LD_PRELOAD=/opt/jre/libfaketime.so.1
ENV DONT_FAKE_MONOTONIC=1
ENV FAKETIME_CACHE_DURATION=0

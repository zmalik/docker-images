FROM zmalikshxil/kafka:2.2.0

RUN apt update -qq &&\
    apt install gettext-base procps -y
RUN rm -rf /var/lib/apt/lists/*

ENV PATH $PATH:/opt/kafka/bin

COPY scripts/* /opt/kafka/
ARG ELK_VERSION

# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/beats/filebeat:${ELK_VERSION}

RUN ./filebeat modules enable nginx

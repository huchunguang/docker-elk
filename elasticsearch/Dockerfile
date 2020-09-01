ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELK_VERSION}
ENV ELK_VERSION ${ELK_VERSION}

# Add your elasticsearch plugins setup here
RUN elasticsearch-plugin install analysis-icu
RUN elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.2.0/elasticsearch-analysis-ik-7.2.0.zip

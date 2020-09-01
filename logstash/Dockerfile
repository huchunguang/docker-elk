ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
COPY logstash/logstash-core/lib/jars/mysql-connector-java-8.0.17.jar /usr/share/logstash/logstash-core/lib/jars

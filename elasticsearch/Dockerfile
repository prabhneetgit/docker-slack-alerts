ARG ELK_VERSION

# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch-oss:${ELK_VERSION}

ADD . /usr/share/elasticsearch/config

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu

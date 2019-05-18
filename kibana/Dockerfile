ARG ELK_VERSION

# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/kibana/kibana-oss:${ELK_VERSION}

ADD . /usr/share/kibana/config

# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>

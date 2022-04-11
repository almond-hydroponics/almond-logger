FROM fluent/fluentd:v1.14-debian-1
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.0.0"]
USER fluent
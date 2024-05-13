FROM fluent/fluentd:v1.17-debian
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.0.0"]
USER fluent
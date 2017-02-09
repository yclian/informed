FROM logstash:5.1

WORKDIR /app
RUN logstash-plugin install logstash-input-imap

CMD ["-f", "/app/logstash.conf"]

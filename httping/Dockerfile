FROM debian:latest

RUN apt-get update && apt-get install -y httping

ENTRYPOINT ["httping"]

CMD ["--help"]

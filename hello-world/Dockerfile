FROM openjdk:7

WORKDIR /app

COPY Hello.java /app

RUN apt update && apt install -y vim

ENTRYPOINT ["tail", "-f", "/dev/null"]

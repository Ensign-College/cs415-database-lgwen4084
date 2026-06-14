FROM ubuntu:22.04

RUN apt-get update && useradd -m myuser && rm -rf /var/lib/apt/lists/*

USER myuser

WORKDIR /home/myuser

CMD ["bash", "-c", "while true; do sleep 3600; done"]

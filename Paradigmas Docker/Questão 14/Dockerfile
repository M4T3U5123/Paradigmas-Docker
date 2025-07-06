FROM ubuntu:latest

WORKDIR /app

RUN apt-get update && \
    apt-get install -y python3 && \
    rm -rf /var/lib/apt/lists/*

COPY process.py .

CMD ["python3", "process.py"]

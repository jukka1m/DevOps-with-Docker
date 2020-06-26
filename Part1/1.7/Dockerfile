FROM ubuntu:16.04

RUN apt-get update && apt-get install -y curl

WORKDIR /usr/app

COPY . .

CMD ["./script.sh"]

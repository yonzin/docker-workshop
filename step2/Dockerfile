FROM debian:buster-slim

LABEL description="This an iad workshop on docker" \
      maintainer="frederick.perrin@iadinternational.com"

RUN apt-get update && apt-get install -y procps

ENV COMPANY="docker"
COPY test.txt /mnt/
EXPOSE 80

CMD ["bash"]

FROM node:18

RUN mkdir -p /app

WORKDIR /app

COPY ./entrypoint.sh /scripts/entrypoint.sh

RUN chmod +x /script/entrypoint.sh

ENTRYPOINT ["/script/entrypoint.sh"]

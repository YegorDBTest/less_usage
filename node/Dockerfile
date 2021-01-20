FROM node:15.5

COPY ./entrypoint.sh /entrypoint.sh

RUN ["npm", "install", "--global", "less"]

ADD ./app /app
WORKDIR /app

ENTRYPOINT ["/entrypoint.sh"]

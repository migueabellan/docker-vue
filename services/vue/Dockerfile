FROM node:latest

RUN yarn global add @vue/cli
RUN yarn global add @vue/cli-init

WORKDIR /www

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/bin/sh", "/entrypoint.sh"]

EXPOSE 8080

CMD ["npm", "run", "dev"]

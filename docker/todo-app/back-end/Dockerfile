FROM node:14-alpine

WORKDIR /path

EXPOSE 3001

ADD ./node_modules.tar.gz .
COPY ./package-lock.json .
COPY ./package.json .

CMD ["npm", "start"]

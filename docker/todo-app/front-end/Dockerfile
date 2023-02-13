FROM node:14-alpine

WORKDIR /path

EXPOSE 3000

ADD ./node_modules.tar.gz .
COPY ./public .
COPY ./src .
COPY ./.env .
COPY ./.gitignore .
COPY ./package-lock.json .
COPY ./package.json .
COPY ./README.md .

CMD ["npm", "start"]

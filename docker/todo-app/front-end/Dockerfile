FROM node:14-alpine

WORKDIR /path

EXPOSE 3000

ADD ./node_modules.tar.gz .
COPY . .

RUN ["npm", "install"]

CMD ["npm", "start"]

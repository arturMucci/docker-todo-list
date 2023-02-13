FROM mjgargani/puppeteer:trybe1.0

WORKDIR /path

ADD ./node_modules.tar.gz .
COPY ./e2e .
COPY ./jest.config.js .
COPY ./package-lock.json .
COPY ./package.json .

CMD ["npm", "test"]

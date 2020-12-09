FROM node:current-slim

WORKDIR /usr/src/app
COPY ./level2/. .

RUN pwd

RUN ls -la

RUN npm install

RUN echo hi this is a test

EXPOSE 3000
CMD [ "npm", "start" ]

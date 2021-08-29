FROM node

WORKDIR /users-service

COPY package.json .

RUN yarn

COPY . .

EXPOSE 7101

CMD yarn db:migrate && yarn watch
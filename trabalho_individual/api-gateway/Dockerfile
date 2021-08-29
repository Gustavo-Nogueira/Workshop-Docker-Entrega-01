FROM node

WORKDIR /api-gateway

COPY package.json .

RUN yarn

COPY . .

EXPOSE 7000

CMD [ "yarn", "watch" ]
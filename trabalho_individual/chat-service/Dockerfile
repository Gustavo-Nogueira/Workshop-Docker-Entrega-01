FROM node

WORKDIR /chat-service

COPY package.json .

RUN yarn 

COPY . .

EXPOSE 7100

CMD [ "yarn", "watch" ]
FROM node

WORKDIR /chat-app

COPY package.json .

RUN yarn 

COPY . .

EXPOSE 7001

CMD [ "yarn", "watch" ]
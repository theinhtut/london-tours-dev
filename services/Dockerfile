FROM node:12

WORKDIR /strapi-app

COPY ./package.json .
RUN yarn install && yarn cache clean
COPY . .

RUN ls -l

CMD ["yarn", "develop"]

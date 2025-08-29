FROM node:lts-alpine3.22
WORKDIR /app

COPY package.json yarn.lock .
RUN yarn install 
COPY . . 

ENTRYPOINT ["node" , "src/index.js"]
EXPOSE 3000

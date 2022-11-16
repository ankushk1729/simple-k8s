FROM node:19-alpine

COPY ./package.json .
RUN npm install
COPY . .

CMD [ "npm", "start" ]
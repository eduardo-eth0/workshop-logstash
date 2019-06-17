FROM node:10-alpine

RUN npm install -g --production json-server

COPY . .

CMD ["json-server","-H","0.0.0.0","db.json"]


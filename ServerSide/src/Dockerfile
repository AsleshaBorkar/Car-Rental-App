FROM node:18

WORKDIR /app

COPY ServerSide/package.json ./

RUN npm install

COPY ServerSide/. .

EXPOSE 5000

CMD ["npm", "start"]

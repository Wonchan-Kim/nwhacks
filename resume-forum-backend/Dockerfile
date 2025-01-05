FROM node:16

WORKDIR /src

COPY ["package*.json", "./"]

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "src/server.js"]

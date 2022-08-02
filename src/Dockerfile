FROM node:16-alpine3.15
COPY ./package*.json ./
WORKDIR /app
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]

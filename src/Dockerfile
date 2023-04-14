FROM node:18.11.0
WORKDIR /app
COPY packag*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]
FROM node:20.12.1
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
CMD ["node", "server.js"]
EXPOSE 8080

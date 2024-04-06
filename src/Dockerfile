FROM node:20.12.1
WORKDIR /app
COPY package*.json .
RUN npm install
RUN npm install -g nodemon
COPY . .
CMD ["nodemon", "server.js"]
EXPOSE 8080

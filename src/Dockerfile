FROM node:18.12.1
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . . 
EXPOSE 8181
CMD ["node", "server.js"]


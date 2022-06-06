FROM node:17.8.0
WORKDIR /app
COPY package*.json ./
RUN npm install --yes
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]

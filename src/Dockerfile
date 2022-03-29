FROM node:14.19.1
WORKDIR /app
COPY package*.json ./
RUN npm install --yes
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
FROM node
WORKDIR /app
COPY package*.json ./
RUN npm install --yes
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
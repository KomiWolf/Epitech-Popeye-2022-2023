FROM node:12-alpine
WORKDIR /result
EXPOSE 80
COPY package.json .
RUN npm install
COPY . .
CMD ["node", "server.js"]

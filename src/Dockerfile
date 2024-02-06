FROM node
WORKDIR /app
COPY package*.json /app
RUN npm cache clean --force
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]

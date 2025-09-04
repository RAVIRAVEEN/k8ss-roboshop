FROM node:18
WORKDIR /app/server.js
COPY package.json /app/server.js
COPY server.js /app/server.js
RUN npm install
CMD [ "node", "server.js" ]

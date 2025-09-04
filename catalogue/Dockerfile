FROM node:18
WORKDIR /app/server.js
COPY package.json /app/server.js
COPY server.js /app/server.js
RUN npm install
ENV MONGO=true
CMD [ "node", "server.js" ]

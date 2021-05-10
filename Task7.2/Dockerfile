FROM node:latest
RUN mkdir /app
WORKDIR /app
RUN npm install express
RUN npm install mysql
COPY server.js /app/server.js
CMD node /app/server.js
EXPOSE 3000

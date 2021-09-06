FROM node:10.23.3-alpine
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY server.js package.json package-lock.json ./
RUN npm install --production
EXPOSE 3000
CMD [ "npm", "start" ]
FROM node:8.9.4-alpine
MAINTAINER sasaki
RUN npm install -g express-generator@4.16.0
ADD . /app/
WORKDIR /app
EXPOSE 3000
CMD ["node", "/app/index.js"]
FROM node:14.16.1-alpine3.13
COPY package*.json ./
RUN npm install
WORKDIR /app
COPY . .
EXPOSE 8080
CMD ["node","app.js"]
FROM node:14.15.0
WORKDIR /app
COPY package*.json ./
RUN npm install && npm i -g pm2
COPY . .
EXPOSE 3000
CMD [ "pm2-runtime", "./index.js" ]

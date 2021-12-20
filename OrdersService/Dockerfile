FROM node:12-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install --production
COPY . .
EXPOSE 9000
CMD ["node", "/app/orders.js"]
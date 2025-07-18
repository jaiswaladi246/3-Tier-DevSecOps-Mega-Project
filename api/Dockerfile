FROM node:22-alpine

WORKDIR /app
COPY package*.json ./
RUN npm install --only=production

COPY . .
EXPOSE 5000
CMD ["node", "app.js"]

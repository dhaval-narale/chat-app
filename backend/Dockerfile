FROM node:18-alpine

WORKDIR /app
COPY server.js .
RUN npm init -y && npm install express

EXPOSE 5001
CMD ["node", "server.js"]

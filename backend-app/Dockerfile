FROM node:18
WORKDIR /app

COPY api/package*.json ./
RUN npm install

COPY api/. .

EXPOSE 5000
CMD ["npm", "start"]

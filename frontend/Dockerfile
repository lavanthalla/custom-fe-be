FROM node:14
WORKDIR /
COPY frontend/package*.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]



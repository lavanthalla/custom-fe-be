FROM node:14
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN ng build --prod

#FROM nginx:alpine
#COPY /app/dist/custom-fe-be /usr/share/nginx/html
#CMD ["nginx", "-g", "daemon off;"]



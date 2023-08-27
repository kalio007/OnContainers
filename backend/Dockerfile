FROM node:20-alpine
USER root
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .h
EXPOSE 5173
CMD [ "npm", "run", "dev" ]
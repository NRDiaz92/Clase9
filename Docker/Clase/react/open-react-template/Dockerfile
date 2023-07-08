FROM node:latest

WORKDIR /app

COPY . .

RUN npm install next

ENTRYPOINT ["npm", "run", "dev"]
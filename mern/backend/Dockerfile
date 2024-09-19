# FROM node:18.9.1

# WORKDIR /app

# COPY package.json .

# RUN npm install

# COPY . .

# EXPOSE 5050

# CMD ["npm", "start"]

FROM node:20.17-alpine

WORKDIR /app

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 5050

CMD ["npm","start"]
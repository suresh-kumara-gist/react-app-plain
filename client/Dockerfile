FROM node:latest

WORKDIR /usr/app

COPY package*.json ./
# RUN npm update
RUN npm install 
# RUN npm ci -qy

# COPY . .

EXPOSE 3000

CMD ["npm", "start"]

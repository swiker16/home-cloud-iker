FROM node:current-alpine

WORKDIR C:\Users\ikerf\Prueba

COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]

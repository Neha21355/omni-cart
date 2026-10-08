FROM node:24-alpine

WORKDIR /OmniCart

COPY package*.json ./

RUN npm i

COPY . .

EXPOSE 5173

CMD ["npm", "run", "dev"]
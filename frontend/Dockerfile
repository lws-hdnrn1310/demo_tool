FROM node:23.6.1-alpine3.20

WORKDIR /demo_tools_product

COPY package.json package-lock.json ./

RUN npm install

COPY . .

CMD ["npm", "run", "dev"]

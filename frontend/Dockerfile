FROM node:alpine3.17
WORKDIR /frontend
COPY package.json .
RUN npm install
COPY . .
EXPOSE 5173
CMD [ "npm", "run", "dev" ]

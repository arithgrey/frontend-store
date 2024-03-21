FROM node:21.6.0

WORKDIR /frontend

COPY package*.json ./

RUN npm install --no-cache

COPY . .

EXPOSE 5173

CMD [ "npm", "run", "dev", "--", "--host", "0.0.0.0"]

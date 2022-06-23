FROM node

WORKDIR /app

COPY package.json .

RUN npm install

ENV PORT 42000

COPY . .

EXPOSE $PORT

CMD ["node", "app.js"]

FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV MONGODB_USERNAME=admin
ENV MONGODB_SECRET=admin

EXPOSE 80

CMD ["npm","start"]
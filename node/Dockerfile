FROM node:15

WORKDIR /usr/src/app

COPY . .
RUN npm init -y
RUN npm install mysql --save
RUN npm install express --save


EXPOSE 3000

CMD ["node","index.js"]
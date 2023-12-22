FROM node:latest
WORKDIR /react-pizza-master
COPY ./react-pizza-master/package.json .
RUN npm install
COPY ./react-pizza-master .
RUN npm run build
EXPOSE 3000
CMD ["npm","start"]

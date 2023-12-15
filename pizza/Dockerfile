FROM node:latest
COPY ./react-pizza-master/package.json .
RUN npm install
COPY ./react-pizza-master .
CMD ["npm","start"]
EXPOSE 3000

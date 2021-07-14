FROM node:14
RUN mkdir /project
WORKDIR /project
COPY . .
RUN npm install
EXPOSE 8000
CMD [ "node", "app.js" ]

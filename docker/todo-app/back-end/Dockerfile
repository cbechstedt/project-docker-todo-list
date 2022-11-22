FROM node:14
EXPOSE 3001
ADD node_modules.tar.gz .
WORKDIR /todo-app/back-end/
COPY . .
CMD [ "npm start" ]
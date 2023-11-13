FROM node:lts

WORKDIR /app

COPY ../../wready/react-app/package*.json ./

RUN npm install

COPY ../../wready/react-app/ /app

EXPOSE 3000

CMD ["npm", "start"]
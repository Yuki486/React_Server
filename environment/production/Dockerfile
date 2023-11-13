FROM node:lts

WORKDIR /app

COPY ../../wready/react-app/package*.json ./

RUN npm install

COPY ../../wready/react-app/ /app

EXPOSE 3000

CMD ["npm", "start"]

# FROM node:lts

# WORKDIR /app

# COPY ./wready/react-app /app/react-app

# WORKDIR /app/react-app

# RUN cd /app/react-app && npm install

# RUN cd /app/react-app && npm run build

# EXPOSE 3000

# CMD ["npm", "start"]
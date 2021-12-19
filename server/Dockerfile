FROM node:lts-alpine as node_build
WORKDIR /usr/src/app
COPY . .
RUN npm install -g npm \
    && npm install
ENV NODE_ENV development
EXPOSE ${PORT}
CMD ["npm", "start"]

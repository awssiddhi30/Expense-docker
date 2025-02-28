FROM node:20
USER  expense
WORKDIR /opt/backend
COPY package.json /opt/backend
COPY *.js  /opt/backend
RUN install npm
ENV DB_HOST=mysql
CMD ["node", "index.js"]
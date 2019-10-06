FROM node
COPY . /app
WORKDIR /app
RUN npm install
USER node
CMD ["/usr/local/bin/node","/app/src/index.js"]


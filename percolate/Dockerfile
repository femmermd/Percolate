FROM node:alpine
EXPOSE 4200
WORKDIR /usr/src/percolate
RUN npm install -g @angular/cli
COPY . .
RUN npm install
CMD ["ng", "serve"]
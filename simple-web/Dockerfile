FROM node:alpine

WORKDIR /home/simpleweb 

COPY ./package.json ./      
RUN npm install

COPY ./ ./      

CMD ["npm", "start"]
FROM node:20
#create /app and set the 
WORKDIR /app
copy package.json .
copy *.js .
RUN npm install
ENV MONGO_URL="mongodb://mongdb:27017/catalogue"\
    MONGO="true"
    CMD ["node","server.js"]


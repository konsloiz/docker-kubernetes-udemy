#Specify base image
FROM node:alpine
#Working directory
WORKDIR /usr/app
#Enable hot-reloading of package.json
COPY ./package.json ./
#Install dependencies
RUN npm install
COPY ./ ./
#Set default command
CMD ["npm","start"]

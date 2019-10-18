FROM node:alpine
WORKDIR '/app'
COPY package.json .
COPY package-lock.json .
RUN npm install
COPY . .
CMD ["npm", "run", "start"]
#This command is refer to package.json file... so start refer
#"scripts": {
#    "start": "node index.js",
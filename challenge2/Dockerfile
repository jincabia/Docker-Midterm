#making an image for Node.js
FROM node:14

#setting the directory
WORKDIR /usr/src/app

#copying package files 
COPY package*.json ./

#installing node dependencies
RUN npm install

#copying the code to the directory
COPY . .

#exposing the port 
EXPOSE 3000

#cmds to run the application
CMD ["node", "server.js"]

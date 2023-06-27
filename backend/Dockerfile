FROM node:14

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./

# Install the application dependencies
RUN npm install

# Bundle app source
COPY . .

# Expose port 9000 for the application
EXPOSE 9000

CMD [ "npm", "run" , "dev" ]
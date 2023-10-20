# Use an official Node.js runtime as a parent image
FROM node:14

# Create a working directory in the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the container
COPY package*.json ./

# Install application dependencies
RUN npm install

# Copy the rest of the application source code to the container
COPY . .

# Expose the port that the application will run on
EXPOSE 5000

# Define the command to run your Node.js application
CMD [ "node", "index.js" ]







# Dockerfile for Server
FROM node:18

# Set working directory
WORKDIR /usr/src/app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the application files
COPY . .

# Expose the port that the server listens to
EXPOSE 5000

# Command to start the server
CMD ["node", "server.js"]

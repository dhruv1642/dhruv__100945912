# Use the node:19.7.0-alpine base image
FROM node:19.7.0-alpine

# Set app folder as the working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json /app
RUN npm install

# Copy the rest of the app's code into the container
COPY . /app

# Expose port 3000
EXPOSE 3000

# Set the default execution command
CMD ["node", "src/index.js"]

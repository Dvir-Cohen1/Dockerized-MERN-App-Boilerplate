# Use a Node.js runtime as the base image
FROM node:14

# Set the working directory to /app
WORKDIR /app

# Copy the package.json and package-lock.json files to the container
COPY package.json .

# Install the project dependencies
RUN npm install -g ts-node
RUN npm install 

# Copy the source code to the container
COPY . .

# Build the TypeScript code
RUN npm run compile

# Expose port 5000 for the application
EXPOSE 5000

# Start the application
CMD ["npm","run", "dev"]
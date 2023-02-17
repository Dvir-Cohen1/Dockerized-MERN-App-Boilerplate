# Use an official Node.js runtime as a parent image
FROM node

# Set the working directory to /app
WORKDIR /app

# Copy the package.json and package-lock.json files to the container
COPY package.json .

# Install dependencies
RUN npm install

# Copy the rest of the application code to the container
COPY . .

# Build the application for production
# RUN npm run build

# Expose port 3000 to the outside world
EXPOSE 5173

# Start the application
CMD ["npm", "run", "dev"]
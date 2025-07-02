# Base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy app files
COPY . .

# Expose backend port
EXPOSE 3061

# Start the server
CMD ["node", "server.js"]


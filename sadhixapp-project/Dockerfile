    FROM node:alpine # Use a lightweight Node.js base image
    WORKDIR /app # Set the working directory inside the container
    COPY package*.json ./ # Copy package.json and package-lock.json
    RUN npm install # Install dependencies
    COPY . . # Copy the rest of your application files
    EXPOSE 3000 # Expose the port your application listens on
    CMD ["node", "index.js"] # Command to run your application
# 1. Start from an existing image
FROM node:16

# 2. Set working directory inside container
WORKDIR /app

# 3. Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# 4. Copy the rest of the application
COPY . .

# 5. Expose the app's port
EXPOSE 8080

# 6. Command to run the app
CMD ["node", "index.js"]

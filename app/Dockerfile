# Use an official Node.js runtime as a base image
FROM node

# Copy the local code to the container
COPY client .

# Build the React app
#RUN npm run build

# Expose the port that the Node server will run on
EXPOSE 3000

# Connect to the Docker network
#NETWORK_MODE="my-network"

# Command to run your application
CMD ["npm", "start"]

#docker build -t only_react_container .
#docker run -p 3000:3000 only_react_container
#docker run -d --network my-network -p 3000:3000 only_react_container
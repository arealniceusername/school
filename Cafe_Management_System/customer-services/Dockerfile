# the base image used
FROM node:18

# working directory 
WORKDIR /app

# installing dependicies
COPY package*.json ./
RUN npm install

# copying the files from the currentdirectory voer to the directory in the container image
COPY . .

# used port 3000 for all ( as mentioned in the requirements )
EXPOSE 3000

# Command to run the app
CMD ["node", "index.js"]
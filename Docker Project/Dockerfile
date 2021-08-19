# Specify Base Image
FROM node:alpine
 
# Work Directory
WORKDIR /usr/app
#Copy some files
copy ./ ./
 
# Install Dependencies
RUN npm install
 
# Startup Command
CMD ["npm", "start"]
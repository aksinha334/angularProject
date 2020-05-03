#image for Angular environment
FROM node

# creating app directory
RUN mkdir /usr/src/app

# setting it as a working directory 
WORKDIR /usr/src/app 

# running the command to install angularCLI
RUN npm install -g @angular/cli

# copying the file to current directory
COPY . . 


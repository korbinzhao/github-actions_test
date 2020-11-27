FROM node:12

# Create app directory
WORKDIR /home/runner/work/github-actions_test/github-actions_test

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
# COPY package*.json ./

RUN ls -l

RUN npm install
# If you are building your code for production
# RUN npm ci --only=production

# Bundle app source
# COPY . .

# EXPOSE 8080
CMD [ "node", "index.js" ]
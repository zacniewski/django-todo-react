FROM node:12-slim

# Set work directory
WORKDIR /app

# Install dependencies
COPY package.json yarn.lock* /app/
RUN yarn install || npm install

# Copy project
COPY . /app/

EXPOSE 3000

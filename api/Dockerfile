FROM node:12.21.0-alpine
WORKDIR /usr/src/app/
COPY . ${API_BACKEND_PATH}/package*.json ./
RUN npm install
COPY . ${API_BACKEND_PATH}/* ./
EXPOSE 7000

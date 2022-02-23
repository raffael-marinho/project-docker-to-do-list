
# FROM node:14-alpine AS build
# WORKDIR /app
# COPY package*.json ./
# RUN npm install
# COPY . .
# RUN npm run build

# FROM nginx:1.16.0-alpine AS prod
# COPY --from=build /app/build /usr/share/nginx/html
FROM node:14-alpine
WORKDIR ./front-end/todo-app 
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]
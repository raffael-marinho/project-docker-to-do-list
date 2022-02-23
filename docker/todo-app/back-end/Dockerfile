FROM mjgargani/puppeteer:trybe1.0
WORKDIR /usr/src/app
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "test"]
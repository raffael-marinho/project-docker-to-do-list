FROM mjgargani/puppeteer:trybe1.0
WORKDIR ./tests/todo-app 
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "test"]
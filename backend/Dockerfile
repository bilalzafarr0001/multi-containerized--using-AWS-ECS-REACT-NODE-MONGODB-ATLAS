FROM --platform=linux/amd64 node:11.15

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

 ENV ATLAS_URI =mongodb+srv://bilal:bilal@cluster0.lcfkrxc.mongodb.net/goals?retryWrites=true&w=majority

CMD ["npm", "start"]
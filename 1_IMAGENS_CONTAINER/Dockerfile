FROM node

WORKDIR /app

#copiar os arquivos package.json para o diretório raiz do container
COPY package*.json .

RUN npm install

#copiar tudo da raiz para o container
COPY . .

EXPOSE 3000

CMD ["node", "app.js"]
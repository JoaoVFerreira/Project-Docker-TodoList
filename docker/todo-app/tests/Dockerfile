FROM mjgargani/puppeteer:trybe1.0 AS build

WORKDIR /usr/app

COPY package*.json ./

ADD /node_modules.tar.gz ./

COPY . .

ENTRYPOINT ["npm", "test"]
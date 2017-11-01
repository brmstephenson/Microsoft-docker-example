FROM trion/ng-cli-e2e:1.4.1

RUN mkdir -p /usr/src/app

WORKDIR /usr/src/app

COPY . /usr/src/app


RUN npm install

EXPOSE 4200

CMD ["npm", "start"]

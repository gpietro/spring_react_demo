# Spring and React.js demo

Demonstration on how to use React.js with Spring when isn't possible to use docker and with a single deployment.
This project is a demo related to this [article](https://medium.com/@pietroghezzi/spring-and-react-js-the-easy-way-5abe8a529058).

## Requirements
- Java SDK v1.6 or higher
- Apache Maven 3.2 or above

## Installation
```shell
cd /apps/demo
yarn install
yarn build
cd ../../
mvn spring-boot:run
```

visit localhost:8080

## To run react app without spring on webpack-dev-server
```shell
cd apps/demo
npm install
npm start
```

visit localhost:3000

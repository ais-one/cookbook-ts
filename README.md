# About

> **TL;DR** NestJS, ReactJS, Typescript cookbook.

NestJS and ReactJS E-commerce Application Example (from Udemy Course by Antonio Papa)

# Features

Folder | Description | Features
---|---|---
[js-node/nest-admin](js-node/nest-admin) | https://www.udemy.com/course/react-nest-admin | example application (e-commerce) backend using NestJS, for use with [js-web/react-admin](js-web/react-admin)
Nest Microservice | Reference | https://github.com/Denrox/nestjs-microservices-example<br>https://www.merixstudio.com/blog/microservice-nestjs/
[js-web/react-admin](js-web/react-admin) | https://www.udemy.com/course/react-nest-admin | example application (e-commerce) frontend using ReactJS, for use with [js-node/nest-admin](js-node/nest-admin)

# QUICK START - ON YOUR LOCAL MACHINE

## Requirements

- Node 16+ LTS
- Npm 8.3.2+
- For Windows, **integrate bash shell to cmd shell** (when installing git), or use git-bash
- Docker

## Optional VS Code Plugins

## Download

```bash
# clone repo and install backend
git clone https://github.com/ais-one/cookbook-ts.git
cd cookbook-ts
```

### NestJS Example

```bash
cd nest-admin
npm run start:dev # create the SQlite database called db.sqlite (in actual should be created using migration), shutdown server once it is fully up and running
npm run seed # seed the data
npm run start:dev # start the server again
```

- Navigate to http://127.0.0.1:3000
- You can use `test.http` file in the `nest-admin` folder file with `VS Code REST Client` plugin to test enpoints

### ReactJS Example

```
cd react-admin
npm run start
```

- Navigate to http://127.0.0.1:3001
- login details: admin@test.com / password

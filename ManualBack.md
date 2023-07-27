# Manual de Uso BackEnd

**Table of Contents**

- [Manual de Uso BackEnd](#manual-de-uso-backend)
  - [About this Project](#about-this-project)
  - [Pre-requisitos:](#pre-requisitos)
  - [Project Setup](#project-setup)
    - [Env Variables](#env-variables)
  - [Run the server](#run-the-server)
  - [Structure Folder](#structure-folder)

## About this Project

An Express template that uses:

- [TypeScript](https://www.typescriptlang.org/)
- [Node 16.x](https://nodejs.org/en/)
- [Express.js 4](https://expressjs.com/)
- [Sequelize v6](https://sequelize.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Yarn](https://yarnpkg.com/)
- [Dotenv](https://github.com/motdotla/dotenv) to read .env files.
- [Eslint](https://eslint.org/) with airbnb configuration, to check

## Pre-requisitos:

- Windows SO.
- WSL: [guia instalación](https://docs.microsoft.com/en-us/windows/wsl/install).
- Linux: [Que es linux?](https://www.redhat.com/es/topics/linux)

**_Todos los comando mostrados a continuacion deben ser corridos en la consola_**

- [Node.js](https://nodejs.org/es/) LTS ([10.x](https://nodejs.org/en/blog/release/v10.18.0/) or [12.x](https://nodejs.org/es/blog/release/v12.13.0/))
  - `nvm install 12`
- [Yarn](https://yarnpkg.com)
  - `npm install -g yarn`
- [Yeoman](https://yeoman.io/).
  - `npm install -g yo`

## Project Setup

To run this project you can either use [docker-compose](https://docs.docker.com/compose/) or run it manually.

If you choose to use docker-compose, you can run the following command to start the project:

```bash
docker-compose up
```

And that's it!

If you choose to run the project manually, you will need to install the following programs:

- [Node 16.x](https://nodejs.org/en/)
- [PostgreSQL](https://www.postgresql.org/)
- [Yarn](https://yarnpkg.com/)

Then you must install the dependencies using the following command:

```bash
yarn install
```

### Env Variables

First you will need to create a .env file in the root of your project. This file will contain the following information:

```text
PORT: By default 3000, but you can change it with this variable
DB_USERNAME: The username for your database
DB_PASSWORD: The password for your database
DB_NAME: The name of your database
DB_PORT: The port in which your database is running (by default 5432)
JWT_SECRET: The secret key used to sign the JWT token
```

## Run the server

Finally, you can run the project in development mode using the following command:

```bash
yarn dev
```

This command will reset the server every time a file changes.

If you wish to run the project normally, you can run the following command:

```bash
yarn start
```

## Structure Folder

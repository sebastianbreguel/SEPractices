**Table of Contents**

- [About The Project](#about-the-project)
  - [Pre-requisitos:](#pre-requisitos)
  - [Project Setup](#project-setup)
  - [Correr la app!](#correr-la-app)
  - [Structure Folder](#structure-folder)

# About The Project

This is a project to build a mobile App, with:

- [TypeScript](https://www.typescriptlang.org/)
- [Next](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/): Fort styles.
- [Axios](https://axios-http.com/): For request.
- [Eslint](https://eslint.org/) and [prettier](https://prettier.io/): For code style.
- [Yarn](https://yarnpkg.com/)

## Pre-requisitos:

- Windows SO.
- WSL: [guia instalación](https://docs.microsoft.com/en-us/windows/wsl/install).
- Linux: [Que es linux?](https://www.redhat.com/es/topics/linux)

**_Todos los comando mostrados a continuacion deben ser corridos en la consola_**

- [Node.js](https://nodejs.org/es/) LTS ([10.x](https://nodejs.org/en/blog/release/v10.18.0/) or [12.x](https://nodejs.org/es/blog/release/v12.13.0/))
  - ` nvm install 12`
- [Yarn](https://yarnpkg.com)
  - ` npm install -g yarn`
- [Yeoman](https://yeoman.io/).
  - ` npm install -g yo`

## Project Setup

- Clonar repositorio:

```sh
 git clone https://github.com/IIC2513-2021-2/s2-grupo-LUPAPU-frontend.git
```

- Instalar dependencias:

```sh
nvm use 12
yarn install
```

- Debes crear un archivo `.env.local`, que tenga las siguientes variables:

```sh
PORT=8000
REACT_APP_API_URL=http://localhost:3000
```

## Correr la app!

Una vez cumplidos todos los requisitos y pasos anteriores, ejecutaremos el siguiente comando:

```sh
yarn start
```

Now go to http://localhost:8000 and start browsing

## Structure Folder

```
src/
├── assets/
│   ├── fonts/ # App fonts
│   ├── icons/ # App icons
|   └── images/ # App images
├── components/ # Global Components
├── navigation/ # React Navigation files
├── styles/ # Global Styles
├── utils/ # Global utils
├── views/ # Views
└── App.jsx
```

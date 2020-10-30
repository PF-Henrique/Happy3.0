<h1 align="center">
  <img src=".github/logo.svg" height="100px" alt="Happy">
</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Next%20Level%20Week-%233-00b8d3?style=for-the-badge&logo=appveyor" alt="Evento Next Level Week 3" />
  <img src="https://img.shields.io/badge/web%3F-ok-00b8d3?style=for-the-badge" alt="Web" />
  <img src="https://img.shields.io/badge/server%3F-ok-00b8d3?style=for-the-badge" alt="Server" />
  <img src="https://img.shields.io/badge/app mobile%3F-No-00b8d3?style=for-the-badge" alt="Aplicativo mobile No" />
  <img src="https://img.shields.io/github/license/PF-Henrique/proffy?color=00b8d3&style=for-the-badge" alt="License" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/languages/top/PF-Henrique/happy?style=for-the-badge&logo=appveyor" alt="GitHub top language" >
  <img src="https://img.shields.io/github/languages/count/PF-Henrique/happy?style=for-the-badge&logo=appveyor" alt="GitHub language count" >
  <img src="https://img.shields.io/github/repo-size/PF-Henrique/happy?style=for-the-badge&logo=appveyor" alt="Repository size" >
  <a href="https://github.com/PF-Henrique/happy/commits/master">
    <img src="https://img.shields.io/github/last-commit/PF-Henrique/happy?style=for-the-badge&logo=appveyor" alt="GitHub last commit" >
  <img src="https://img.shields.io/badge/made%20by-Rocketseat-15c3d6?style=for-the-badge&logo=appveyor" alt="Made by Rocketseat" >
  </a>
</p>

<br>

<p align="center">
  <a href="#bookmark-about">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-technologies">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#wrench-tools">Ferramentas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#package-installation">Instalação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">Licença</a>
</p>
</strong>
<br>

<p align="center">
    <img alt="Screens" src=".github/happy-screens.png" height="350px" />
</p>

## :bookmark: Sobre

**Happy** é uma plataforma para conectar instituições de cuidados infantis com pessoas interessadas em ajudar. Este projeto foi implementado durante a **Next Level Week #3** da **[Rocketseat](https://rocketseat.com.br/)**. A Next Level Week é um evento online gratuito promovido pela Rocketsat, em que durante 5 dias desenvolvemos uma aplicação completa. Na trilha Omni, a proposta foi criar uma aplicação web e mobile em que lares adotivos podem cadastrar seus endereços e informações para pessoas visitarem.
<br>
## 📸 Screenshots

<p align="center">
  <strong>Tela Web</strong> <br />
  <img src="./.github/demo.gif" alt="Demonstração da plataforma Happy" />
</p>
## :computer: Tecnologias

-  **[Typescript](https://www.typescriptlang.org/)**
-  **[Node.js](https://nodejs.org/)**
-  **[Express](https://expressjs.com/)**
-  **[TypeORM](https://typeorm.io/#/)**
-  **[SQLite](https://www.sqlite.org/)**
-  **[ReactJS](https://reactjs.org/)**
-  **[React Native](http://facebook.github.io/react-native/)**
-  **[Expo](https://expo.io/)**
-  **[Axios](https://github.com/axios/axios)**

<br>

## :wrench: Ferramentas

- **[VisualStudio Code](https://code.visualstudio.com/)**
- **[Insomnia](https://insomnia.rest/)**
- **[Google Chrome](https://www.google.com/chrome/)**
- **[DataGrip](https://www.jetbrains.com/pt-br/datagrip/)**

<br>

## :package: Instalação

### :heavy_check_mark: **Pré-requisitos**

Os seguintes softwares devem estar instalados:
  
  - **[Node.js](https://nodejs.org/en/)**
  - **[Git](https://git-scm.com/)**
  - **[NPM](https://www.npmjs.com/)** or **[Yarn](https://yarnpkg.com/)**
  - **[Expo](https://expo.io/)** 
  - **[Expo App](https://play.google.com/store/apps/details?id=host.exp.exponent)**

<br>

## 💅 Layout

- [Layout Web](https://www.figma.com/file/HQccUZfXuT5m3vYGzvALre/Happy-Web-(Copy)?node-id=0%3A1)
- [Layout Mobile](https://www.figma.com/file/n90wRP36uV41qpNsMNU73d/Happy-Mobile-(Copy))

## 🛠 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

Frontend Web
- [ReactJS](https://pt-br.reactjs.org)
- [Framer Motion](https://www.framer.com/motion/)
- [Leaflet](https://leafletjs.com)
- [React Leaflet](https://react-leaflet.js.org)
- [Toastify](https://www.npmjs.com/package/react-toastify)
- [Styled Components](styled-components.com/)
- [Axios](https://github.com/axios/axios)
- [React Icons](https://react-icons.github.io/react-icons/)
- [Typescript](typescriptlang.org/)
- [React Router](https://reactrouter.com/)

Frontend Mobile
- [React Native](https://reactnative.dev)
- [Expo](https://expo.io)
- [React Navigation](https://reactnavigation.org)
- [Typescript](typescriptlang.org/)
- [Styled Components](styled-components.com/)
- [Axios](https://github.com/axios/axios)
- [React Native Maps](https://github.com/react-native-maps/react-native-maps)

Backend
- [NodeJS](https://nodejs.org/)
- [Express](https://expressjs.com/pt-br/)
- [Typescript](https://typescriptlang.org/)
- [TypeORM](https://typeorm.io#/)
- [Postgres](https://www.postgresql.org)
- [Docker](https://www.docker.com)
- [Multer](https://www.npmjs.com/package/multer)
- [Yup](https://www.npmjs.com/package/yup)

## 📱💻 Instruções

### :arrow_forward:	**Rodando as aplicações**

- :package: API

```sh
  $ cd server
  # Dependencies install.
  $ yarn # or npm install
  # Data base creation.
  $ yarn yarn typeorm migration:run # or npm run yarn typeorm migration:run
  # API start
  $ yarn start # or npm start
```

- :computer: Web app

```sh
  $ cd web
  # Dependencies install.
  $ yarn # or npm install
  # Running web app
  $ yarn start # or npm start
```

- :iphone: Mobile app

```sh
  $ cd mobile
  # Dependencies install.
  $ yarn # or npm install
  # Running mobile app
  $ yarn start # or npm start
```

<br>

## 🐛 Issues
Se as imagens não carregarem no mobile, será necessário mudar 
[o link da linha 7](https://github.com/guivictorr/happy/blob/master/backend/src/views/images_view.ts)
de http://localhost:1337 para o link que está acima do QR CODE na página do Expo

## 🤔 Como contribuir

- Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`.

Depois que o merge da sua pull request for feito, você pode deletar a sua branch.

## 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](#) para mais detalhes.
 

<p align="center">
  <a href="https://devfel.com/" rel="noopener">
 <img  src="https://devfel.com/imgs/devfel-logo-01.JPG" alt="DevFel"></a>
</p>

<h1 align="center">Project Repositories CRUD and Likes</h1>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">

This application performs the CRUD (Create, Read, Update, Delete) of project repositories. <br/><br/>
In addition, it is possible to like a registered repositories, increasing the number of likes by 1 each time the route is called. <br/><br/>
This project was done using Javascript, Node and Express</p>

---

## 📝 Table of Contents

- [Application Features](#features)
- [Dependencies](#dependencies)
- [Built Using](#built_using)
- [Getting Started](#getting_started)
- [Acknowledgements](#acknowledgements)
- [Licenses](#licenses)
- [Authors](#authors)

---

## 🧐 Application Features <a name = "features"></a>

With this application the client can access the following routes<br/>

1. GET /repositories → list all repositories. <br/>
1. POST /repositories → create a repository. <br/>
1. PUT /repositories/:id → update a repository. <br/>
1. POST /repositories/:id/like → add a like to a repository. <br/>
1. DELETE /repositories/:id → delete a repository by id. <br/>

---

## 🔁 Dependencies <a name = "dependencies"></a>

Some project library dependencies includes but are not limited to:

- "cors": "^2.8.5",
- "express": "^4.17.1"
- "uuid": "^8.3.2"
- "jest": "^26.6.3",
- "nodemon": "^2.0.7",

---

## ⛏️ Built Using <a name = "built_using"></a>

- [JavaScript](https://www.javascript.com/) - Programming Language
- [Express](https://expressjs.com/) - Server Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment
- [Insomnia](https://insomnia.rest/) - Rest Client

---

## 🏁 Getting Started <a name = "getting_started"></a>

You can clone the repository through Command Prompt or Terminal just by typing:

```sh
git clone https://github.com/devfel/list-projects.git
```

or download the zip from the green **"Code"** button.

Install dependencies packages with <b>yarn</b>

```sh
yarn
```

With the dependencies installed run <b>yarn dev</b> to bring up the server. To execute the tests run <b>yarn test</b>.

---

## 🎉 Acknowledgements <a name = "acknowledgements"></a>

- Created based on a [RocketSeat](https://rocketseat.com.br/) challenge.
- Full description in Brazilian Portuguese: [Trilha Node.js - Desafio 03](https://www.notion.so/Desafio-03-Corrigindo-o-c-digo-c15c8a2e212846039a367cc7b763c6dd)

---

## 📝 Liceses <a name = "licenses"></a>

- Distributed under the MIT License - see the [LICENSE.md](https://github.com/devfel/list-projects/blob/master/LICENSE.md) file for details.

---

## ✍️ Author <a name = "authors"></a>

- [@devfel](https://devfel.com/) - Luiz Flávio Felizardo

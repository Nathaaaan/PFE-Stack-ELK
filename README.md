# PFE-Stack ELK
<div id="top"></div>

<h3 align="center">PFE Stack ELK</h3>

  <p align="center">
    Projet de fin d'étude Equipe 10 Estimacloud
    <br />
    <br />
  </p>

<!-- TABLE OF CONTENTS-->
<details>
  <summary>Sommaire</summary>
  <ol>
    <li>
      <a href="#about-the-project">Informations du projet</a>
      <ul>
        <li><a href="#built-with">Réalisé avec</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Pour commencer</a>
      <ul>
        <li><a href="#prerequisites">Pré-requis</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Informations du Projet


This is the frontend part of the project. It is used as an Angular Web Application.
The frontend made with Angular CLI will use HTTP Requests to the backend to manipulate data and manipulate indirectly the database.

With the application it's possible to:
* Get information of all sensitivities
* Create a sensitivity
* Delete a sensitivity


<p align="right">(<a href="#top">Back to top of page</a>)</p>



### Réalisé avec

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [Angular](https://angular.io/)
* [TypeScript](https://www.typescriptlang.org/)
* [JavaScript](https://developer.mozilla.org/fr/docs/Web/JavaScript)
* [Node JS](https://nodejs.org/en/)

<p align="right">(<a href="#top">Back to top of page</a>)</p>



<!-- GETTING STARTED -->
## Pour commencer

Instructions to get the project working locally on the machine. But it's not recommanded here because we have already a solution to build the whole project with only two command lines using Docker.

### Pré-requis

It's important to have Docker installed on the machine, also Node JS of course.

### Installation

We use Docker to build the project by using this command:
```sh
docker build -t frontcloud .
```

Then this command for running the project:

```sh
docker run -d -it -p 80:80/tcp --name frontendcloud frontcloud
```


<p align="right">(<a href="#top">Back to top of page</a>)</p>


<img src="/adonisCrud.png" align="center"></img>
<h1 align="center">AdonisJs CRUD</h1>
<p align="center">
  <br/>
  A simple backend AdonisJs CRUD with user authentication.
</p>

<p align="center">
  <a aria-label="NodeJs version" href="https://github.com/nodejs/node/blob/master/doc/changelogs/CHANGELOG_V12.md#12.14.1">
    <img src="https://img.shields.io/badge/node.js@lts-12.14.1-informational?logo=Node.JS"></img>
  </a>
</p>


## Instalation

To install the dependencies and to execute, clone the project on your computer an execute:
```bash
# First, install Adonis CLI
$ npm install --global @adonis/cli

# Enter on project directory
$ cd adonisJsCrud

# Install dependencies
$ npm install

# Create and choose your BD (PostGres, Sqlite, Mysql etc.) and set database informations at .env file using .env.example as an example
$ npm install --save {your database name: pg | mysql | sqlite3}

# Generate APP_KEY if empty:
$ adonis key:generate 

# Run Migrations
$ adonis migration:run

# Run server:
$ adonis serve --dev

# running on port 3333
```
## You can import Insomnia workspace to test the application
[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=adonisJsCrud&uri=https%3A%2F%2Fraw.githubusercontent.com%2FdiegoAndrade777%2FadonisJsCrud%2Fmaster%2FInsomnia_2020-08-21.json)

Made with ♥ by Diego Andrade :wave: [Get in touch!](https://www.linkedin.com/in/diego-rodrigo-de-andrade-98a0271a0/)


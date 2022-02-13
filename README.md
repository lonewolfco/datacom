# DataCom

[![License: MIT](https://img.shields.io/badge/License-MIT-lightgreen.svg)](https://opensource.org/licenses/MIT)

[GitHub Repo](https://github.com/lonewolfco/datacom)


## Table of Contents
- [Description](#description)
- [User Story](#userstory)
- [Functionality Criteria](#fc)
- [UI & Video Walkthrough of Application](#video)
- [Getting Started](#gettingstarted)
- [Languages Used](#languages)
- [License](#license)

---

## Description
<a name="description"></a>
Datacom is a back-end data warehouse for an e-commerce platform. Datacom utilizes Express.js API to use Sequelize to interact with a MySQL database.



## User Story
<a name="userstory"></a>

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Functionality Criteria
<a name="fc"></a>

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## UI & Video Walkthrough of Application
<a name="video"></a>
<a href="https://www.loom.com/share/26f6f6d1e8194a1bbf935835d85a09f3">
    <p>DataCom - Watch Video</p>
    <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/26f6f6d1e8194a1bbf935835d85a09f3-with-play.gif">
  </a>


## Getting Started
<a name="gettingstarted"></a>

You’ll need to use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

Use the `schema.sql` file in the `db` folder to create your database with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.

### Languages Used
<a name="languages"></a>

* `JavaScript`
* `Express`
* `Node.JS`
* `NPM`
  * `Sequelize`
  * `MYSQL2`
  * `dotenv`

  

### License
<a name="license"></a>

MIT License

Copyright (c) 2022 Lonewolfco (Lo Selby)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

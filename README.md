[![Javascript Badge](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=for-the-badge)]() [![NodeJs Badge](https://img.shields.io/badge/NodeJs-339933?logo=node.js&logoColor=FFF&style=for-the-badge)]() [![PostgreSQL Badge](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=FFF&style=for-the-badge)]() [![Sequelize Badge](https://img.shields.io/badge/Sequelize-52B0E7?logo=sequelize&logoColor=FFF&style=for-the-badge)]() [![Insomnia Badge](https://img.shields.io/badge/Insomnia-4000BF?logo=insomnia&logoColor=FFF&style=for-the-badge)]()

# [E-commerce Back End](https://github.com/domdecap/ecommerce-back-end)



## Description

This is a working backend for an e-commerce website. It is written to utilize Sequelize for the route notation.

## Technologies

I used JavaScript, Node, pg, npm, PostgreSQL, Sequelize, and Insomnia.

## Install

Prerequisites: [NodeJs](https://nodejs.org/en) ```v20.12.2```
[PostgreSQL](https://www.postgresql.org/) ```v16.2```

1. Clone this repo to your local machine.
2. Open in code editior (I used VS Code).
3. Open a new instance of the integrated terminal.
4. Run ```npm i``` to install dependencies.
5. Log in to PostgreSQL by typing ```psql -U postgres``` and entering your password.
6. Run ```\i db/schema.sql``` to create the database and tables.
7. Close out of Postgres console.
8. Open new console.
9. Run ```node seeds/index``` to seed the tables.

## Usage

After following installation instructions, run ```node server``` in the integrated terminal to launch the employee tracker. From there, you should be able to check that all of the routes are function properly by checking them in Insomnia. View Demo video to see them in action.

## Demo




https://github.com/domdecap/ecommerce-back-end/assets/33850184/3521f53e-5500-4723-9964-6d9446dc7417





## Contributions

I received help from my tutor Mampuru on how to fix my Create Product route. I utilized ChatGPT to help create and debug the routes.

## 📜 License

MIT License

Copyright (c) 2024 Dominic DeCapite

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


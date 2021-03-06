# Products-API

**A product system made with NestJS. It's a service where you list products, create products or even delete them.**

## What I used in this project

- NodeJS
- NestJS
- Sequelize
- TypeScript

## What I learned doing this project

- **NestJS** - It was my first time using this amazing framework. I have learned many new amazing things, such as setting routes, setting controllers of API and setting models for the database. I am really excited with this new tech, I'm sure it will improve my development skills.

- **Sequelize** - With this project I also learned this ORM, wich helped me a lot with managing the MySQL database, with it's decorators, things got so much easier.

- **TypeScript** - I've just learned TypeScript, and doing this project helped me get the fundamentals real solid.

## Requirements

- You've got to install [MySQL](https://mysql.com/downloads) to run this app

## How to run it locally

1. Run `git clone` and clone the repository </br>

2. Run `npm install` on the directory.</br>

3. Create in the root of your repository the file .env and set your password

4. Edit database information on `./src/app.module.ts`

5. Run `npm start:dev` on terminal

## Routes and Methods of the API

`GET` `/products` -> Return a list of all produts </br>
`GET` `/products/:id` -> Return a specific product based on id </br>
`POST` `/products/create` -> Create a new product based on the data of the request </br>
`PUT` `/products` -> Update a specific product based on request id </br>
`DELETE` `/products/:id` -> Delete a specific product based on id </br>

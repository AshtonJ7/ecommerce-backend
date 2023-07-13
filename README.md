# Ecommerce-Backend

This is the back end for an e-commerce site. Express.js API was used and configured to use Sequelize to interact with a MySQL database. This application isn't be deployed and run on use the local server. 


## User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
```
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

## Tech Stack

**Server:** Node, Express, MySQL database, MySQL2, Sequelize, dotenv.
## Run Locally

Clone the project

```bash
  git clone https://github.com/AshtonJ7/ecommerce-backend.git
```

Install dependencies

```bash
  npm install
```

Set up My SQL

```MYSQL
- mysql -u root -p
- Enter mySQL password
- source db/schema.sql
- QUIT
```

Database Seeding 

```Seed
node seeds/index.js
```

Start the server

```bash
  npm run start
```

## Walkthrough

Setting up Database:

https://drive.google.com/file/d/1SzBpmkKogM1X1rtyl_2PfKsOKjcU6Tkv/view?usp=sharing

Open API GET routes in Insomnia Core for categories, products, or tags & Post/Put & Delete tested for Categories:

https://drive.google.com/file/d/1Kfj9X-we_rt1GGmZdaSm0hrzFmWexunR/view?usp=sharing

Post and Put and delete tested for Products:

https://drive.google.com/file/d/1M7qxdN3YmKxp1kLTXKJgrfPUmCaZ7X-z/view?usp=sharing

Post, Put and deleted tested for Tags:

https://drive.google.com/file/d/1S9SbM_VUxQvO0RJch-t6oVmt3VmVKMmF/view?usp=sharing

## Screenshot

![image](https://github.com/AshtonJ7/ecommerce-backend/assets/62944042/1fc7ea28-cd30-434e-8a69-662b0bd7f1de)

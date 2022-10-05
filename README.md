# 13-E-Commerce-Back-End

## Challenge User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```


## Challenge Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```


## General Info

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms is beneficial for any full-stack web developer.

The goal of this challenge is to build the back end for an e-commerce site by modifying starter code.  This will be done by configuring a working Express.js API to use Sequelize to interact with a MySQL database.


## Applied Technologies

* [NPM](https://www.npmjs.com/)
* [Node.js](https://nodejs.org/en/docs/)
* [MySQL](https://dev.mysql.com/doc/refman/8.0/en/what-is-mysql.html)
* [Express.js](https://expressjs.com/en/guide/routing.html)
* [Dotenv](https://www.npmjs.com/package/dotenv)
* [Sequelize](https://sequelize.org/)



## Application Functionality

The following video demos how to run the schema in the mySQL shell, seeding the databse, and starting the application:

![James Li Ecommerce Backend](./assets/13-e-commerce-back-end-demo-gif-part1.gif)

The following videos demo the GET, PUT, POST, DELETE routes for the Categories/Products/Tags models of the application:

![James Li Ecommerce Backend](./assets/13-e-commerce-back-end-demo-gif-part2.gif)

![James Li Ecommerce Backend](./assets/13-e-commerce-back-end-demo-gif-part3.gif)

![James Li Ecommerce Backend](./assets/13-e-commerce-back-end-demo-gif-part4.gif)

Links to the video demos:
* Part 1 - Schema, Seed, Starting Application: https://drive.google.com/file/d/1v372D00itzQptdtiPdYQkau9xpoX8437/view
* Part 2 - GET, PUT, POST, DELETE Routes for Categories: https://drive.google.com/file/d/1yk4MT7q9ZsPZS3fYi_5OauhooWa_R5dI/view
* Part 3 - GET, PUT, POST, DELETE Routes for Products: https://drive.google.com/file/d/1x3t2EgWBtw4q4RkwDyRku-vcJ7PKWG41/view
* Part 4 - GET, PUT, POST, DELETE Routes for Tags: https://drive.google.com/file/d/14ecXTzY1Vwn8BrBfJ_Od3wMuHU8EarkZ/view
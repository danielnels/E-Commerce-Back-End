# E-COMMERCE BACK-END

 ## Description
A back end application for an e-commerce site that tracks products, tags, and categories. Started with a working Express.js API and configured it to use Sequelize to interact with a MySQL database using routes and models.
This application performs CRUD operation on the available database which utilises GET all items,GET one item, POST new entries, PUT updating enteries, and DELETE entries including the associated model data. Mysql database is using sequelize and backend operations can be seen and manliunated in Insomnia.

 ## Table Of Contents
  * [Description](#description)
  * [User Story](#user-story)
  * [This Weeks task](#this-weeks-task)
  * [Acceptance Criteria](#acceptance-criteria )
  * [Walkthrough Video](#walkthrough-video)
  * [App image ](#app-image)
  * [Deployed Application Link](#deployed-application-link)
  * [Usage](#usage)
  * [Technologies Used](#technologies-used)
  * [Packages](#packages)
  * [Questions](#questions)
  * [License](#license)
  

## This weeks Task

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

Your task is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.

Because this application won’t be deployed, you’ll also need to provide a link to a walkthrough video that demonstrates its functionality and all of the acceptance criteria being met. You’ll need to submit a link to the video and add it to the readme of your project.


## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
```

## Acceptance Criteria

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
## Usage

To use this application:

* Clone the GitHub repository at: https://github.com/danielnels/-Awesome-Note-Taker-Express.js.git
Download and install node.js.

* To automatically install dependencies, run "npm i" 

* Be sure to include your MySQL user/password information in .env file.

Database Connection
* mysql -u root -p
* source schema.sql
* npm run seed [To seed the file]

Run the app

* npm start [To start the server] and navigate to http://localhost:3001/ in your browser OR Use Insomnia Core
Usage

## Technologies Used

#### * Node.js
#### * Insomnia 


## Packages

#### * Package.json
#### * express
#### * Mysql2
#### * dotenv
#### * sequelize

    
## Walkthrough Video



## App image

![Note-taker](https://user-images.githubusercontent.com/94213022/156104569-2f2e7d79-6675-47f3-84e3-9240b4f25ff1.png)


## Deployed Application Link


## Questions
  Please e-mail me if you have any questions about this App
  danieln@newground.net.au 

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

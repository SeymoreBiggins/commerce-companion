# Commerce Companion (Back End)

[installation video](https://drive.google.com/file/d/1kGAq4NAqsSf2Oaz3Z0QR2K92EL9MApdi/view)

[usage video](https://drive.google.com/file/d/1-8xcIJUQ6Zudah2bU-KO_wkMIz8D15WZ/view)

## Contents

* [Description](#description)
* [Images](#images)
* [Installation](#installation)
* [Usage](#usage)
* [Contact](#contact)

## Description
Commerce Companion (Back End) is a back end framework for an e-commerce site using mysql2 and sequelize. It is fully equipped for CRUD interfacing and is ready for front end development.

## Images
images go here

## Installation
1. install Node Package Manager and relevant packages in cmd
  * $ npm init -y
  * $ npm install mysql2 sequelize dotenv

2. create a .env file with your mysql password
  * image goes here

## Usage
1. Open mysql interface to instantiate the database and then exit mysql
  * $ mysql -u root -p
  * $ source db/schema.sql
  * $ quit

2. Seed the program and run through the cmd interface
  * $ npm run seed
  * $ npm start

3. You should see something like this to signal the database is up and running
  * App listening on port 3001!

4. Open up insomnia and test the API routes (see video above)

## Contact
For any questions or concerns, feel free to contact me by email [zachharris024@gmail.com](mailto:zachharris024@gmail.com) or reach out to me on my gitHub [SeymoreBiggins](https://https://github.com/SeymoreBiggins).
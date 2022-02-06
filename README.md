# E commerce backend 

![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Description

This express appliction handles an e-commerce backend. By using Sequelize it allows the user to interact with the a SQL database.  



## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](https://i.gyazo.com/38dbd2728b672d75b0440880f8d41d8b.png)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation

To install this project simply navigate to the root folder or even individual files you wish to run and use 'npm i' in your termimal. Additionally you will need to source the Schema file which is the database. You can do this by running it in the SQL command line, your own command line if you have enabled SQL, or use a manager like SQL workbench. 
There will be instructional videos below to help you achieve this. 

## Usage

Once you have installed the required packages. You will need to do a few things in order to get this running. After installing the required dependencies. Use the command line and enter 'npm run watch'. This will start your server. It should print out a message in the console telling you it is listening on port 3001. 

Then you need to make sure you have created your databse because we will run the seeds. You should have already done this as mentioned in the installation steps, however if you haven't now would be a good time do so. Please refer to videos below for help. But if the database is created then you can simply enter 'npm run seed' which will seed the database with data for you. 

After that you can use an API client like insomnia to interact with the database. The format is JSON. There are 3 routes. 

- Catergories
- Products
- Tags

All 3 routes allow for Get, Get by ID, Post, Put and delete requests. Again instructional videos below will demonstrate how to do this. 

## Screenshot

In addition to the screenshot. Here is a link to the video walkthrough of how to use the application - https://www.youtube.com/watch?v=jlqegJoddGk

![Screenshot](https://i.gyazo.com/05bdec0a98e884026a8b32cee2ef93e4.png)

- Instructional videos 

Walkthrough of setting up Database and running server - https://youtu.be/yVwG_7BDbUk

Category routes - https://youtu.be/bLKM4TxU-w4

Product Routes - https://youtu.be/v1NuF3FKRVY

Tag Routes - https://youtu.be/hFGzP3JeWHE

## License

https://opensource.org/licenses/MIT

This project is under the license of MIT

## Contributing

Alistair Houghton

## Tests

Not Applicable 

## Questions

If you have any questions about this project, you can contact me at my github . More projects available here https://github.com/Alistairhoughton.

![license badge](/images/license-MIT-License-yellow.svg)

# E-Commerce Backend

## Description

This is a backend for an ecommerce website. It uses express and sequelize for the routes and mysql for the database. The database structure includes a Category table, Product table, Product Tag table, and Tag table. This backend could be used with a front end to enter, adjust, and display product information. This link shows a video walkthrough:

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation

Login to mysql and source schema.sql to create the database, then seed it by running npm seed. Then run npm i to download dependencies and npm start to start the application.

## Usage

To use the ecommerce backend, a route request testing application, like insomnia, must be used. Start the application by running the sequence shown in the installation section. Then start insomnia.

There are 15 routes created that can be used. There are three pieces of information the routes pull/post/put/or delete information from, these are Category, product, and tag. Each piece of information has the following routes: GET All, GET by ID, POSt new, PUT by ID, and DELETE by ID. If running the server locally, these routes can be tested by inputting:
http://localhost:3001/api/"categories or products, or tags"/"ID if Getting, putting, or deleting by ID".
These photos show the routes and format for JSON for some routes:
![categories Get All](/images/categories-get-all.png)
![categories Get by ID](/images/categories-get-by-id.png)
![categories Post](/images/categories-post.png)
![categories Put](/images/categories-put.png)
![categories Delete](/images/categories-delete.png)
![Products Get All](/images/products-get-all.png)
![Products Get by ID](/images/products-get-by-id.png)
![Products Post](/images/products-post.png)
![Products Put](/images/products-put.png)
![Products Delete](/images/products-delete.png)
![Tags Get All](/images/tags-get-all.png)
![Tags Get by ID](/images/tags-get-by-id.png)
![Tags post](/images/tags-post.png)
![Tags Put](/images/tags-put.png)
![Tags Delete](/images/tags-delete.png)

## License

This software is covered by the MIT License. Please refer to this link for further details:
[MIT License](https://opensource.org/licenses/MIT)

## Contributing

NA

## Tests

NA

## Questions

Github: https://github.com/jaugsbu2

Please email any questions to: joshua.augsburger08@gmail.com

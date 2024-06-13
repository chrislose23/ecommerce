# E-Commerce Back End

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)

## Description

![JavaScript](https://img.shields.io/badge/JavaScript-blue) ![Node.js](https://img.shields.io/badge/Node.js-blue) ![Express.js](https://img.shields.io/badge/Express.js-blue) ![MySQL](https://img.shields.io/badge/MySQL-blue) ![License](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is a back-end API for an e-commerce platform built using Express.js and Sequelize. The API is designed to handle various operations for managing categories, products, and tags within the e-commerce application. The key functionalities include creating, reading, updating, and deleting (CRUD) data in a PostgreSQL database.

## Installation

1. **Environment Setup**:
   - Create an `.env` file and add your PostgreSQL database name, username, and password.
   
2. **Database Setup**:
   - Run schema and seed commands to set up and seed the development database.

3. **Starting the Application**:
   - Run the command to start the server. This will sync the Sequelize models to the PostgreSQL database.

4. **Testing the API**:
   - Use Insomnia to test the GET, POST, PUT, and DELETE routes for categories, products, and tags.

## Usage

To interact with the API, you can use an API client such as Insomnia. To retrieve all categories, make a GET request to the /api/categories endpoint. For a specific category by its ID, use the /api/categories/:id endpoint, replacing :id with the actual category ID. 

Similarly, to get all products or a specific product by its ID, make GET requests to /api/products and /api/products/:id respectively. The same applies to tags, using the /api/tags and /api/tags/:id endpoints.

To create a new category, product, or tag, make POST requests to /api/categories, /api/products, and /api/tags with JSON bodies containing the necessary details. To update an existing category, product, or tag by their ID, use PUT requests to the /api/categories/:id, /api/products/:id, and /api/tags/:id endpoints with updated information.

Finally, to delete a category, product, or tag by their ID, make DELETE requests to /api/categories/:id, /api/products/:id, and /api/tags/:id respectively. Customize the request payloads as needed to fit your specific use cases.

## License

Licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Questions

[My GitHub Repo](https://github.com/chrislose23/ecommerce)

[My Email Address](chrislose23@gmail.com)


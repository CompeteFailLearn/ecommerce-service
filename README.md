# E-commerce RESTful Web Service
This project is an E-commerce RESTful web service that provides endpoints to interact with product data. The backend is powered by PostgreSQL, and the service is built using Spring JPA and Spring MVC. The service supports full CRUD (Create, Read, Update, Delete) operations and returns appropriate HTTP status codes based on the operation outcomes.

## Features

- **GET api/products**: Fetches all product data from the PostgreSQL database.
- **POST api/product**: Allows users to post new product details along with a photo.
- **GET /product/{id}**: Retrieves the details of a specific product by its ID.
- **GET /products/search**: Retrieves the details of a specific product by the search query.
- **PUT /product/{id}**: Updates the details of a specific product by its ID.
- **DELETE /product/{id}**: Deletes a specific product by its ID.



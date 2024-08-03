# Simple API with Laravel

This is a simple API built with Laravel, a PHP framework. The project was created for studying RESTful API development, with the goal of working with this technology in the future. Through this project, I learned about routes, models, controllers, and seeders, as well as the fundamentals of HTTP responses and RESTful design principles.

## Learning Objectives

- Understand the basics of Laravel framework.
- Learn how to set up routes, models, controllers, and seeders.
- Gain practical experience in building a RESTful API.
- Explore HTTP methods and status codes.
- Implement CRUD operations.
- Manage database migrations and seeding.

## Key Concepts

### Routes

Routes are defined to handle different HTTP requests. In this project, I learned how to set up API routes using Laravel's routing system. For example:

- `GET /api/books` - Retrieve a list of all books.
- `POST /api/books` - Create a new book.
- `GET /api/books/{id}` - Retrieve a specific book by its ID.
- `PUT /api/books/{id}` - Update a specific book by its ID.
- `DELETE /api/books/{id}` - Delete a specific book by its ID.

### Controllers

Controllers are used to handle the logic for each route. I created a `BooksController` to manage the CRUD operations for the `Books` model. This helped me understand how to separate concerns and keep the code organized.

### Models

Models represent the data structure and interact with the database. I created a `Books` model to define the properties and relationships of the book data. This also included setting up fillable attributes for mass assignment.

### HTTP Responses

Understanding HTTP responses is crucial for API development. I learned how to send appropriate HTTP status codes and messages for different scenarios, such as successful data retrieval, creation, updates, and error handling.

### Database Migrations and Seeders

Database migrations are used to manage the database schema, while seeders are used to populate the database with initial data. I learned how to create and run migrations and seeders to set up the project database.

### Authentication

Although the focus was on learning the basics, I also explored Laravel Sanctum for API authentication. The `/api/user` endpoint is protected by Sanctum authentication middleware.

## Conclusion

This project provided a solid foundation for understanding and building RESTful APIs with Laravel. The hands-on experience with routes, controllers, models, and HTTP responses has prepared me for more advanced topics in API development and integration.

## Acknowledgments

- Laravel documentation and community
- Online tutorials and resources
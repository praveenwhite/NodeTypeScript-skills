# NodeTypeScript-skills
Node.js and TypeScript skills  Test


1-Hour Machine Test (Node.js + TypeScript):
Objective: Assess candidate's ability to build, optimize, and test a small Node.js app using TypeScript, with focus on modern backend patterns.

Question:
Task: You are tasked with building a small REST API service that manages a list of products. The service should allow users to perform basic CRUD operations and fetch a list of products based on category and pagination.

Part 1: API Development (45 minutes)
Create a new Node.js project:

Use TypeScript with proper tsconfig.json.
Install the following libraries:
express
pg (for PostgreSQL) or sqlite3 (for in-memory database)
jest for testing (if time permits)
Setup a Basic Express Server:

Create an Express server with TypeScript.
Implement REST API Endpoints:

POST /products: Add a new product with the following fields:

id (UUID)
name (string)
price (number)
category (string)
stock (number)
GET /products: Fetch a paginated list of products with filtering based on category.

Query params: category, page, and limit.
PUT /products/:id: Update the details of an existing product by its id.

DELETE /products/:id: Delete a product by its id.

Database Integration:

Use an in-memory database (sqlite3 or similar) to store and retrieve the product data.
Implement proper error handling, ensuring that invalid operations (e.g., deleting a non-existent product) return appropriate error responses.
TypeScript Setup:

Ensure that you use TypeScript to define clear interfaces or types for:
Product object
API request/response types
Part 2: Bonus Task (Optional - 15 minutes)
Testing:

Write basic unit tests using jest for at least one of the API routes (POST /products and GET /products).
Performance Consideration:

Add pagination for the GET /products route. Make sure the API can handle large datasets efficiently (use appropriate SQL queries or filters).
Evaluation Criteria:
Code Organization: How well-structured is the project?
TypeScript Proficiency: Proper use of interfaces/types and TypeScript best practices.
API Functionality: Working CRUD operations and pagination.
Error Handling: Proper handling of potential errors or bad inputs.
Code Quality: Clean, readable code.
Testing: Implementation of meaningful unit tests (if completed).

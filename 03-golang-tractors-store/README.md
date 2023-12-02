# Test Task: Tractor Store REST API on Golang

## Objective

Develop a RESTful API for a Tractor Store application, where users can view tractors, place orders, and manage inventory. 
The API will use Golang as the programming language and PostgreSQL for data storage.

Follow the provided [OpenAPI Specification](./tractor-store.openapi.yaml) for implementing the API endpoints.
You can use the [tractors.json](./tractors.json) file to populate the database with sample tractor data.

## Requirements

1. Tractor Catalog:
   - Implement endpoints to list tractors, view detailed information about a specific tractor, and add new tractors to the catalog.
2. Order Placement:
   - Create endpoints for customers to place orders. Each order should reference one or more tractors and include quantities.
3. Inventory Management:
   - Implement endpoints to update tractor inventory, such as adding stock or marking tractors as sold out.

## Bonus (Optional)

1. User Management:
   - If time permits, add a simple user management system with roles (e.g., customer, admin).

## Evaluation Criteria

- Code organization and readability
- Functionality of the API endpoints
- Proper use of PostgreSQL database
- Compliance with OpenAPI specification
- Proper error handling

## Time Limit

This task is designed to be completed within approximately 3 hours for a developer who is familiar with programming, PostgreSQL, and maybe new to Golang.

## Submission Guidelines

- Submit the project as a public or private GitHub repository.
- Ensure the repository contains clear commit history to demonstrate your workflow.
- Include a README file with instructions on how to run the application and any other necessary documentation.
- If any libraries or frameworks are used (other than Golang), mention them in the README.

## Additional Notes

- Feel free to use any additional libraries or frameworks you find useful for this task, but make sure to include them in your README.
- Good luck!

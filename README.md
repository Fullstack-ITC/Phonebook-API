# Task: Phonebook API with Express.js and Local File System

## Objective
Create a simple phonebook API using Express.js which performs CRUD (Create, Read, Update, Delete) operations on phone numbers. The data should be stored in a local file.

## Specifications

### Setup
- Initialize a new Node.js project.
- Install Express.js using npm.
- Setup a basic Express.js server.

### Local File Database
- Use the built-in 'fs' module in Node.js to read from and write to a local file.
- The file should store phone numbers in JSON format.

### API Endpoints
- `GET /phonebook`: Retrieve all phone numbers from the local file.
- `POST /phonebook`: Add a new phone number to the local file. The body should contain a field named 'phoneNumber'.
- `PUT /phonebook/:phoneNumber`: Update an existing phone number in the local file. The `:phoneNumber` parameter will be the phone number to be updated.
- `DELETE /phonebook/:phoneNumber`: Delete a specific phone number from the local file using the `:phoneNumber` parameter.

### Error Handling
- Handle scenarios where a phone number might not exist in the local file for update or delete operations.
- Provide meaningful error messages to the client.

### Testing
- Use tools like Postman or any REST client to test each of the endpoints.
- Ensure that each operation (fetch, save, update, delete) works as expected with the local file database.

# Story-Spoil-API-Manual-Testing
This repository contains manual API testing for the Story Spoil API, performed using Postman. The goal of this project is to validate various API endpoints for managing users, story spoilers, and authentication within the Story Spoil platform.

## Project Overview
The Story Spoil API allows users to create, update, search, and delete story spoilers. The project also supports user authentication, allowing registered users to manage spoiler-related data. Below are the APIs tested in this project:

- Create User: Allows the creation of new user accounts.
- Get Authentication Token: Retrieves an authentication token for user access.
- Create Spoiler: Allows users to submit a new story spoiler.
- Get All Story Spoilers: Fetches a list of all story spoilers.
- Search Story Spoilers: Allows users to search for story spoilers by keywords.
- Update Spoiler: Allows users to modify an existing story spoiler.
- Delete Story Spoiler: Allows users to remove a spoiler from the system.
- Supported Methods: Retrieves all the supported methods of the API.

## Tested API Endpoints
The following endpoints were tested:

- POST /api/User/Create: Create a new user.
- POST /api/Auth/Token: Get authentication token.
- POST /api/Spoiler: Create a new story spoiler.
- GET /api/Spoiler: Get all story spoilers.
- GET /api/Spoiler/Search: Search for story spoilers by keyword.
- PUT /api/Spoiler/{id}: Update an existing story spoiler.
- DELETE /api/Spoiler/{id}: Delete a story spoiler.
- GET /api/Info/Methods: List supported methods.

## Tools Used
- ### Postman: For creating and running API test cases.
- ### GitHub: For version control and repository management.
  
## How to Use
1. Clone the repository:
   
git clone https://github.com/yourusername/StorySpoil-API-Testing.git

2. Navigate to the project directory:
   
cd StorySpoil-API-Testing

3. Run the test cases by following the test collection within the Postman workspace.

## License
This project is licensed under the MIT License.

# User Management Page

For this challenge you will create a simple user management remote API, for example REST or gRPC, suitable for consumption by a client. 

The API will allow administrators to create, update, list and delete users.

## The Data Model
- A user account will have the following information:
    - Email address
    - Access level: “admin”, “read”, or “write”
    - status: “active”, “inactive”, "invited"
- When a user is created, their status is invited by default. Their email address and access level should be part of the create request.

## The Backend
The backend you will build will be responsible for storing user account information. It should expose endpoints to:

- Create a user
- Retrieve a list of users
- Change a user's access level
- Delete a user

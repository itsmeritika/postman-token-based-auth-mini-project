# postman-token-based-auth-mini-project
Postman mini project demonstrating token-based authentication and API testing using the Reqres API.
# Postman Token-Based Authentication Mini Project

## Description
Postman mini project demonstrating token-based authentication and API testing using the Reqres API[](https://reqres.in).

## Overview
This project includes:
- A Postman collection with requests for login (to obtain a token) and subsequent authenticated requests (e.g., get user).
- An environment with variables (like base URL and token storage).

## How to Use
1. Import the collection and environment JSON files into Postman.
2. Run the "login" request to generate and store the token.
3. Run other requests – the token will be used automatically via Postman variables.

## Files
- `token-based-auth-collection.json`: The main Postman collection.
- `reqres-environment.json`: The Postman environment (with variables like `baseUrl` and `authtoken`).

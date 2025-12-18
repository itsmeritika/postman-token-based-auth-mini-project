# Postman Token-Based Authentication Mini Project

# Postman Token-Based Authentication Mini Project

## Description
Postman mini project demonstrating token-based authentication and API testing using the Reqres API[](https://reqres.in).

## Overview
This project includes:
- A Postman collection with requests for login (to obtain a token) and a subsequent request using the token.
- An environment with variables (like `baseurl` and `authToken` for token storage).

## How to Use
1. Import the collection (`token-based-auth-collection.json`) and environment (`reqres-environment.json`) into Postman.
2. Select the environment.
3. Run the "login" request — it will extract and store the token automatically.
4. Run the "get user" request — the token will be used as Bearer auth.

## Files
- `token-based-auth-collection.json`: The main Postman collection.
- `reqres-environment.json`: The Postman environment.



## Screenshots
![image alt](https://github.com/itsmeritika/postman-token-based-auth-mini-project/blob/c395858e897e418264f37d4522b34c62a36d3932/screenshot-get-user.png)
![image alt](https://github.com/itsmeritika/postman-token-based-auth-mini-project/blob/c395858e897e418264f37d4522b34c62a36d3932/screenshot-login.png)
![image alt](https://github.com/itsmeritika/postman-token-based-auth-mini-project/blob/c395858e897e418264f37d4522b34c62a36d3932/screenshot-collection-run.png)


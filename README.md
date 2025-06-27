# Testing-WebServices-booking-api

## Prerequisites

- **Node.js** (v10 or higher)

## Installation

Install Newman globally using npm:

npm install -g newman


## Files

- **restful_booker.postman_collection.json**  
  The Postman collection with all API requests and tests.

- **restful_booker_env.postman_environment.json**  
  The Postman environment with required variables (such as `username` and `password`).

## Running the Collection

To run the collection with Newman, use the following command:

newman run restful_booker.postman_collection.json -e restful_booker_env.postman_environment.json

This will execute all requests in the collection using the specified environment and display the results in your terminal.

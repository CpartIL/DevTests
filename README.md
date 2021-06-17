# Cpart Developer Test

## GENERAL
- The purpose of this assignment is to review your coding and Architecture abilities.
- All code written will be zipped and send by Email to yaniv@cpart.co.il or will be shared in a shared GIT repository 
- This repository contains a basic structure of the Apps for your convinience 

## The assignment
In this task you are require to provide a webpage constructed from the following projects: 

    1. An Angular App containing 1 page (Homepage) 
    2. An MVC .net core API that will serve as an API for the angular App

### .NET Core API - Description
The API project should contain: 

    1. a single Endpoint for use in order to get users list (/api/users)
        - The data will come from an Ajax call to https://reqres.in/api/users?per_page=200 
    2. a single Endpoint for use in order to get users list (/api/products)
        - The data will come from an Ajax call to https://reqres.in/api/products?per_page=200 
**Important notes:**
- Please make sure to Cache the result for efficiency (your decision how to cache it exactly) 

### Angular App - Description 
The angular app contains only 2 pages with a table inside. 

For your convenience, we already created a static table with dummy data inside which as part of the task you will need to replace with a dynamic content from the API. 

- You are require to connect to the API from the angular app using a service. 
- You are require to fill the table from the API (all fields in the table should be dynamic 
- The final result of the app should contain 2 pages: 
    - A users table (connected to API) 
    - A Products table (connected to API) 


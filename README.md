# Tourism-DBMS_Project

# Airport Statistics Web Application

## Overview

This web application provides airport statistics based on various parameters such as airport, gender, quarter, and age. Once logged in, users are redirected to the landing page where they can enter their search criteria to retrieve statistics. The search can be narrowed down by specifying the airport location, gender, age, and quarter, with location and year being mandatory fields. To access the statistics, users must sign up or log in if they already have an account.

## Working Principle

After entering the search criteria, the application splits the entered locations or years separated by commas and manages the search criteria accordingly. This split array is then used to construct the SQL query to fetch the relevant statistics from the database.

## Features

- **Airport Statistics:** View statistics based on airport, gender, quarter, and age.
- **Search Functionality:** Search for statistics by specifying airport location and year.
- **User Authentication:** Sign up and log in to access the statistics.

## Requirements

- PHP
- HTML
- CSS

## Installation

1. There's no need to install any server-side dependencies as the application is built using PHP, HTML, and CSS.

2. Set up your web server to serve the PHP files.

## Usage

1. **Sign Up/Log In:**
    - If you are a new user, sign up with your details.
    - If you already have an account, log in with your credentials.

2. **View Statistics:**
    - Once logged in, you will be redirected to the landing page.
    - Specify the airport location and year to search for statistics.
    - Choose parameters like gender, quarter, and age to filter the results. Location and year are mandatory fields for the search.

3. **Logout:**
    - Click on the 'Logout' button to log out from your account.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

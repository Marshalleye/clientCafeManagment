# Frontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.9.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


# Cafe Management System

![Cafe Management System](https://example.com/cafe-management-system.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [How to Contribute](#how-to-contribute)
- [Support and Contact](#support-and-contact)

## Introduction

Welcome to the Cafe Management System! This project aims to streamline and enhance the operations of cafes, making it easier for cafe owners and staff to manage their business efficiently. Whether you run a small cozy cafe or a bustling coffee shop, our system provides a user-friendly interface and powerful features to optimize your daily tasks.

## Features

- **Menu Management**: Create, update, and organize your menu items with ease. Add descriptions, images, and categorize them to attract your customers.

- **Order Processing**: Manage incoming orders, track their status, and ensure seamless communication between the kitchen and serving staff.

- **Table Reservations**: Allow customers to reserve tables online and keep track of the reservations in real-time.

- **Billing and Payments**: Generate bills for orders, accept various payment methods, and keep track of financial transactions.

- **Inventory Management**: Monitor your inventory levels, receive notifications for low stock items, and manage supplier information.

- **User Roles**: Differentiate user access with role-based permissions. Assign roles like admin, staff, or manager for secure data handling.

## Technologies Used

- **Front-End**: HTML, SCSS, JavaScript, Angular

- **Back-End**: Java

- **Database**: MySQL (or any preferred database)

- **Authentication**: JSON Web Tokens (JWT)

## Installation and Setup

Follow the instructions below to set up the Cafe Management System on your local machine:

1. **Clone the Repository**: Begin by cloning this repository to your local environment using the following command:

`git clone https://github.com/your-username/cafe-management-system.git`


2. **Front-End Setup**: Navigate to the `front-end` directory and install the required dependencies:

`cd cafe-management-system/front-end`
`npm install`


3. **Back-End Setup**: Go to the `back-end` directory, install dependencies, and set up the environment:

`cd ../back-end`
`npm install`
`cp .env.example .env`


Modify the `.env` file with appropriate database credentials and other settings.

4. **Database**: Set up your preferred database (MongoDB recommended) and ensure it's running.

5. **Run the Application**: Start the back-end server and front-end development server:


# Embedded Payment Application

This is a sample embedded payment application that demonstrates the integration of a PHP backend with an Angular frontend to handle payment processing. The application allows users to make payments securely within your website using a third-party payment gateway.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Embedding in Your Website](#embedding-in-your-website)
- [Security](#security)
- [Contributing](#contributing)
- [License](#license)

## Features

- Simulates Payment Gateway api with Mobile Money and Credit Card Options.
- Secure handling of payment transactions.
- An Angular frontend for a user-friendly payment experience.
- A PHP backend for processing payments.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed.
- PHP server set up.
- Angular CLI installed.

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/devcema/embedded.git

## Project Structure
frontend/: Angular frontend code.
backend/: PHP backend code.
docs/: Project documentation and README files.
LICENSE: The license file for the project.
README.md: This file.

## Configuration
Frontend Configuration:

Open frontend/src/environments/environment.ts and set your API URL.
Replace the placeholder API URL with the URL of your backend API.


Backend Configuration:
create the transaction logs table. Table structure included in file

## Embedding in your website

Set the href of your payment button to the url of hosted angular homepage/initiatepayment

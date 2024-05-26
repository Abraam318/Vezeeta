# Veezeta

![Veezeta](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimages.storychief.com%2Faccount_3659%2FBookingSystemforDoctors_b1467ae295ebc9f96502eb88a3e3513f_2000.jpg&f=1&nofb=1&ipt=a57486162c0ee4ee660acd2c68c3a87e39faaaf4d3f53a6040c5efd3bfd2a5d2&ipo=images)


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Functionality](#functionality)
- [Code Structure](#code-structure)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the Veezeta System! Our program is designed to connect patients with doctors quickly, easily, and securely. Upon running the program, the first message you'll hear is "Welcome to Veezeta System." The system ensures user privacy by encrypting passwords in a file, ensuring only the user knows their password.

## Features

- Fast and secure patient-doctor connection.
- Encrypted password storage for enhanced security.
- Simple interface for easy navigation.
- Personalized welcome message upon login.
- User-friendly functions for both doctors and patients.

## Functionality

Our project is divided into three main files:

1. **interface.h**: Contains all necessary libraries and function definitions.
2. **source.cpp**: Contains declarations of all functions.
3. **main.cpp**: Contains the main function.

## Code Structure

### Sound Function

This function greets users with "Welcome to Veezeta System" upon running the program and bids farewell with "Thank you for using Veezeta" upon program exit.

### Current Date Function

This function interacts with the operating system to obtain the current date. The system uses this date to schedule patient appointments in the future, with a maximum of 7 days from the current date.

### Sign Up Function

Enables users to create a new account as a doctor or a patient. Includes multiple checks to ensure data integrity, such as email uniqueness and gender validation.

## Usage

To use the Veezeta System:

1. Clone the repository.
2. Compile and run the project using your preferred IDE or command line.
3. Follow the on-screen prompts to navigate the system as a doctor or a patient.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/abraam318/Veezeta.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Veezeta
    ```
3. Compile and run the project.

## Contributing

We welcome contributions! Please fork the repository and submit a pull request.
![Veezeta System](path-to-another-image.jpg)

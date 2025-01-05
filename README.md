# Software_Testing_Project

## Overview
This repository contains automated tests for the Swag Labs e-commerce platform implemented as part of the SE302 Software Testing and Maintenance course. The tests are written in TypeScript using Playwright.

## Prerequisites
- Node.js installed on your machine
- npm (Node Package Manager)

## Setup
1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/your-username/QA-Project.git
   cd QA-Project

2. Initialize the project with npm.
    ```bash
    npm init

3. Install Playwright.
     ```bash
     npm install @playwright/test
     npx playwright install

## Running Tests

### Run All Tests 
    
    
    npx playwright test 

### Run All Tests (Headed Mode)
    
    
    npx playwright test --headed
    
### Run All Tests (Headed Mode)
   
    
    npx playwright test --browser=YourBrowserOfChoice
    
### Run Smoke Tests Only
   
    
    npm run tests:smoke
    
    
### Run Regression Tests Only
    
    
    npm run tests:regression
    

## Test Scenarios

### Smoke Tests
    Checkout
    Registration
    Home Page
    Log in/Log out
    Search

### Regression Tests
    Advanced Search
    Category
    Invalid Checkout
    Invalid Create Account
    Invalid Login
    Footer
    NavBar
    Orders and Returns
    Promo Banners
    Search Items

## Thank you

We sincerely appreciate the teaching assistant's time and expertise in assessing this project. We value the work you do to help us develop as students, and your advice and criticism are priceless. 

We appreciate your dedication to our educational process!

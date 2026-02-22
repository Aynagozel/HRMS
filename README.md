# HRMS Automation Framework

## Overview
This project is a Java-based test automation framework built using Selenium WebDriver, TestNG, and Maven. It automates core HRMS functionalities and follows the Page Object Model (POM) design pattern. The framework supports data‑driven testing with Excel files and includes reusable utilities and reporting capabilities.

## Technologies Used
- Java
- Selenium WebDriver
- TestNG
- Maven
- Apache POI (Excel data handling)
- Page Object Model (POM)

## Project Structure
HRMS/  
├── src/main/java/        # Base classes and utilities  
├── src/test/java/        # Test classes and page objects  
├── regression.xml        # TestNG suite  
├── Hello.xlsx            # Test data  
└── HrmsTestData.xlsx     # Data-driven Excel file

## Key Features
- Page Object Model (POM) architecture  
- Data‑driven testing with Excel  
- Reusable utility classes  
- Screenshot capture on failure  
- Regression suite execution  

## Test Coverage
- Login functionality  
- Employee management  
- Leave workflows  
- Data‑driven scenarios  
- Full regression suite  

## How to Run Tests
mvn clean test  
mvn clean test -DsuiteXmlFile=regression.xml

## Reports
test-output/index.html

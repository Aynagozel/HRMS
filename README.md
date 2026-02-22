# HRMS Automation Framework

This project is a Java-based automation framework built with Selenium WebDriver, TestNG, and Maven to automate core HRMS functionalities. It follows the Page Object Model architecture and supports data‑driven testing using Excel.

## 🚀 Technologies Used
- Java
- Selenium WebDriver
- TestNG
- Maven
- Apache POI
- Page Object Model (POM)

## 📁 Project Structure
HRMS/
├── src/main/java/        # Base classes, utilities  
├── src/test/java/        # Tests and page objects  
├── regression.xml        # TestNG suite  
├── Hello.xlsx            # Test data  
└── HrmsTestData.xlsx     # Data-driven Excel file

## 🧪 Test Coverage
- Login  
- Employee management  
- Leave workflows  
- Data-driven scenarios  
- Regression suite

## ▶️ How to Run
mvn clean test  
mvn clean test -DsuiteXmlFile=regression.xml

## 📊 Reports
test-output/index.html


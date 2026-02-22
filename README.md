# HRMS Automation Framework

This project is a Java-based automation framework built using Selenium WebDriver, TestNG, and Maven to automate core functionalities of a Human Resource Management System (HRMS). The framework follows industry-standard automation practices and demonstrates skills in UI automation, data-driven testing, and scalable framework design.

## 🚀 Technologies Used
- Java
- Selenium WebDriver
- TestNG
- Maven
- Apache POI (Excel data handling)
- Page Object Model (POM)
- TestNG XML Suite

## 📁 Project Structure
HRMS/
│
├── src/
│   ├── main/java/        # Core framework, utilities, base classes
│   └── test/java/        # Test cases and page objects
│
├── test-output/          # TestNG reports
├── target/               # Maven build output
├── pom.xml               # Maven dependencies
├── regression.xml        # TestNG suite file
├── Hello.xlsx            # Test data
└── HrmsTestData.xlsx     # Data-driven testing Excel file

## 🧪 Test Coverage
- Login tests
- Employee management
- Leave request workflows
- Data-driven scenarios
- Full regression suite

## ▶️ How to Run Tests
mvn clean test  
mvn clean test -DsuiteXmlFile=regression.xml

## 📊 Reporting
Reports are generated at:  
test-output/index.html

## 🎯 Purpose of the Framework
- Fast and reliable regression testing
- Scalable and maintainable architecture
- Data-driven testing support
- Real-world automation framework structure

## 👩‍💻 Tester
Aynagozel  
QA Automation Engineer

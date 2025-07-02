# 🛒 OpenCart Web Application – BDD Automation Framework

This project is a Behavior-Driven Development (BDD) automation framework for testing the OpenCart web application. It covers **Login** and **Registration** scenarios using **Cucumber with Java**, following industry-standard practices such as Page Object Model (POM), Data-Driven Testing, and continuous integration with **Jenkins** and **Selenium Grid**.

---

## 🚀 Technologies Used

- **Programming Language:** Java
- **BDD Tool:** Cucumber (Gherkin syntax)
- **Test Runner:** JUnit
- **Build Tool:** Maven
- **Automation Tool:** Selenium WebDriver
- **Design Pattern:** Page Object Model (POM)
- **Reporting:** Extent Reports & Junit Reports
- **CI/CD:** Jenkins
- **Parallel Execution:** Selenium Grid
- **Data Source:** Excel (Apache POI)
- **Logging:** Log4j2

---

## 📁 Project Structure

src/test/java/
├── factory/ # Base class for WebDriver setup
├── pageObjects/ # POM classes for application pages
├── stepDefinitions/ # Step definitions for Cucumber scenarios
├── testRunner/ # TestRunner for executing Cucumber features

src/test/resources/
├── config.properties # Configuration file for environment settings
├── extent.properties # Report configurations
├── log4j2.xml # Logging configuration

Features/
├── Login.feature
├── LoginDDTExcel.feature
├── Registration.feature

testData/
├── Opencart_LoginData.xlsx # Test data for data-driven testing

test-output/
├── SparkReport_TIMESTAMP/ # Execution reports

---

## ✅ Features Automated

- 🔐 **Login Functionality**
  - Valid and invalid login flows
  - Data-Driven Testing using Excel

- 📝 **User Registration**
  - Registration with different input validations
  - Field-wise validation and positive test scenarios

---

## ⚙️ How to Run

### 🖥️ Pre-requisites

- Java 8+
- Maven
- Git
- Jenkins (optional)
- Selenium Grid (optional)
### 💻 Steps to Execute using CMD

1.Navigate to the project directory:
cmd
cd opencart_cucumber_bdd

2.Run tests using Maven:
cmd
mvn clean test

3.OR, run using the batch file:
cmd
run.bat

4.Reports will be generated in:
test-output\SparkReport-TIMESTAMP\
📊 Reporting
Extent Reports: Detailed HTML reports.

Spark Report: Timestamped reports under test-output/.

📌 Highlights
✨ Clean and modular Page Object Model

🔁 Data-Driven testing with Excel

🧵 Parallel execution with Selenium Grid

🧪 Continuous Integration with Jenkins

📄 Structured feature files using Gherkin


👨‍💻 Author
Madhu
📫 madhurgukt691@gmail.com
🌐 https://www.linkedin.com/in/madhumallabathula/


📃 License
This project is for educational and demonstration purposes only.



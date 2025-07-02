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

### 📂 src/test/java

- 📁 factory  
  - `BaseClass.java` – WebDriver setup and base utilities

- 📁 pageObjects  
  - `LoginPage.java`  
  - `RegistrationPage.java`  
  - `AccountRegistrationPage.java`  
  - `CheckoutPage.java`  
  - `HomePage.java`  
  - `MyAccountPage.java`  
  - `SearchPage.java`  
  - `ShoppingCartPage.java`  

- 📁 stepDefinitions  
  - `Hooks.java` – Setup/Teardown methods  
  - `LoginSteps.java` – Step definitions for login  
  - `RegistrationSteps.java` – Step definitions for registration

- 📁 testRunner  
  - `TestRunner.java` – Executes feature files with JUnit

---

### 📂 src/test/resources

- `config.properties` – App URLs, credentials, and config values  
- `extent.properties` – Extent Report configuration  
- `log4j2.xml` – Logging configuration file

---

### 📂 Features

- `Login.feature` – Basic login scenario  
- `LoginDDTExcel.feature` – Login with data-driven test  
- `Registration.feature` – User registration scenario

---

### 📂 testData

- `Opencart_LoginData.xlsx` – Test input data for login

---

### 📂 test-output

- `SparkReport_<timestamp>/` – Auto-generated Spark/Extent reports

---

### 📦 Other Root Files

- `run.bat` – Batch file to run tests via CMD  
- `pom.xml` – Maven build and dependency file  
- `README.md` – Project overview (this file)
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



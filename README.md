# autoqa-test-automation---1-
AutoQA Pro is a robust, scalable, and maintainable end-to-end test automation framework built using Selenium WebDriver, Java, and TestNG for an E-Commerce web application.  It follows industry best practices like the Page Object Model (POM) design pattern, ensuring clean separation of concerns, reusability, and easy maintenance.

**🚀 AutoQA Pro – E2E Test Automation Framework
**
AutoQA Pro is a scalable and maintainable end-to-end Selenium automation framework built for an E-Commerce application using Selenium WebDriver, TestNG, and Java.

It follows the Page Object Model (POM) design pattern and industry best practices to ensure clean architecture, reusability, and reliability.

**Features** :
✅ End-to-End automation (Auth → Product → Cart → Checkout)
✅ Page Object Model (POM) design
✅ Explicit Wait handling (no Thread.sleep)
✅ Data-driven testing using TestNG DataProviders
✅ Config-driven framework (no hardcoding)
✅ Screenshot capture on failure
✅ ExtentReports HTML reporting
✅ Cross-browser support (Chrome, Firefox)

**Test Coverage** :
🔐 Authentication
    Login (valid & invalid)
    Logout
  User Registration
    Product Module
    Search products
    Browse by category
    Verify product details
  🛒 Cart Module
    Add to cart
    Remove from cart
    Validate cart updates
💳 Checkout Module
    Complete order flow
    Redirect validation (without login)
⚠️ Form Validation
    Empty field validation
    Invalid email validation
  
** Project Structure **:

SeleniumPOMFramework/
│
├── src/main/java/
│   ├── base/           → Base classes (WebDriver setup)
│   ├── pages/          → Page Object classes
│   ├── utils/          → Utilities (waits, config, screenshots)
│   └── dataproviders/  → Test data (JSON/Excel)
│
├── src/test/java/
│   ├── tests/          → Test classes
│   └── listeners/      → TestNG listeners
│
├── src/test/resources/
│   ├── config.properties
│   └── testdata.json
│
├── testng.xml          → Test suite configuration
├── pom.xml             → Maven dependencies
└── screenshots/        → Failure screenshots


  **Tech Stack**:
Language: Java
Automation: Selenium WebDriver
Test Framework: TestNG
Build Tool: Apache Maven
Reporting: ExtentReports
Driver Management: WebDriverManager

** Configuration ** :
All configurable values are stored in:  src/test/resources/config.properties

Example:
browser=chrome
baseUrl=https://automationexercise.com
timeout=10

▶️ **How to Run**:
1. Clone the repository
git clone https://github.com/your-username/AutoQA-Pro.git
cd AutoQA-Pro
2. Run tests
mvn clean test


**Reporting**
HTML reports generated using ExtentReports
Screenshots captured automatically on test failure
Reports include:
Test status (Pass/Fail)
Execution details
Failure evidence

**Framework Highlights**
No hardcoded values (fully config-driven)
No WebDriver code inside test classes (strict POM)
Reusable utilities for wait, config, and screenshots
Clean separation of concerns

**Objective** :

This project demonstrates:
**Real-world automation framework design**   **Scalable test architecture**    **Industry-level best practices in Selenium automation**

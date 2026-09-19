# 🧪 Fundamentals — Cypress Test Automation

A Cypress test automation project created to practice and demonstrate **end-to-end web testing** against the [Practice Expand Testing](https://practice.expandtesting.com/) website.

The project contains automated test cases covering Cypress fundamentals and browser-based automation exercises.

## 🎯 Project Overview

This repository is focused on learning and applying **Cypress test automation** through practical browser testing.

The tests interact with a real practice website and demonstrate how automated tests can be organized into Cypress test specifications.

### Objectives

* Practice Cypress fundamentals
* Automate browser-based user interactions
* Write structured end-to-end tests
* Validate web application behavior automatically
* Build familiarity with Cypress test syntax and commands
* Practice automation against realistic web scenarios

## 🧪 Test Suites

The repository currently contains two Cypress test files:

### `fundamentals.cy.js`

Contains tests focused on Cypress fundamentals and basic browser automation.

### `automation-exercise.cy.js`

Contains additional browser automation exercises targeting the practice website.

The repository also contains a project README with a link to supporting automated-testing documentation.

## 🌐 Test Application

The automated tests target:

**Practice Expand Testing**

https://practice.expandtesting.com/

This website provides a collection of practice pages designed for learning and testing web automation.

## 🛠️ Technology Stack

| Technology        | Purpose                                   |
| ----------------- | ----------------------------------------- |
| **Cypress**       | End-to-end browser automation             |
| **JavaScript**    | Test implementation                       |
| **Node.js / npm** | Project runtime and dependency management |
| **Git/GitHub**    | Version control and project hosting       |

## 📁 Project Structure

```text
Fundamentals-Cypress/
│
├── automation-exercise.cy.js
├── fundamentals.cy.js
└── README.md
```

The current repository contains these two Cypress test specifications and the project README.

## ⚙️ Prerequisites

Before running the tests, install:

* Node.js
* npm
* Cypress

Verify Node.js:

```bash
node --version
```

Verify npm:

```bash
npm --version
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/andylaique/Fundamentals-Cypress.git
```

### 2. Navigate to the project

```bash
cd Fundamentals-Cypress
```

### 3. Install dependencies

```bash
npm install
```

### 4. Open Cypress

```bash
npx cypress open
```

Select the appropriate test specification from the Cypress interface and run it against the practice website.

## ▶️ Run Tests from the Command Line

To execute the Cypress tests in headless mode:

```bash
npx cypress run
```

To run a specific specification:

```bash
npx cypress run --spec "fundamentals.cy.js"
```

Or:

```bash
npx cypress run --spec "automation-exercise.cy.js"
```

## 🔍 Testing Approach

The project follows a browser-based end-to-end testing approach:

```text
Cypress
   │
   ▼
Launch Browser
   │
   ▼
Open Practice Application
   │
   ▼
Interact With UI
   │
   ▼
Assert Expected Behavior
   │
   ▼
Test Result
```

This approach allows user-facing workflows to be tested automatically rather than manually repeating the same browser interactions.

## 📚 Learning Outcomes

This project provides practical experience with:

* Cypress test structure
* JavaScript-based test automation
* Browser interaction
* DOM element selection
* Assertions
* End-to-end testing
* Test specification organization
* Running tests interactively
* Running tests from the command line
* Automated validation of web application behavior

## 📖 Supporting Documentation

The repository's existing README references additional documentation about automated testing.

## 🔮 Potential Extensions

Future improvements could include:

* Adding more test scenarios
* Organizing tests into feature-based directories
* Adding reusable Cypress custom commands
* Introducing fixtures and test data
* Adding API testing
* Adding negative/error-path tests
* Adding test reporting
* Integrating Cypress tests into CI/CD
* Adding screenshots and videos for failed tests
* Introducing smoke and regression test suites

## 👨‍💻 Author

**Andy Laique**

GitHub:
https://github.com/andylaique

Repository:
https://github.com/andylaique/Fundamentals-Cypress

## 📄 License

No license is currently specified in the repository.

---

**Project:** Fundamentals-Cypress
**Focus:** End-to-End Test Automation
**Framework:** Cypress
**Language:** JavaScript

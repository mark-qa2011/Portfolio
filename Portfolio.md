# 🛠️ Mark Anthony Palma | QA Test Engineer Portfolio

**Passionate QA Engineer specializing in automated and manual testing. Focused on finding bugs early, optimizing test coverage, and ensuring high-quality software delivery.**

🌐 **Links:** [LinkedIn Profile](https://www.linkedin.com/in/markanthonypalma/) | palma.markanthony@gmail.com

💻 **Tech Stack & Tools:** Playwright, Dart, Postman, Python, TypeScript, JavaScript, Git, JIRA, Jenkins

---

## 🚀 Featured Project: E-Commerce Platform Test Automation Suite
<!-- **Project Link:** [Link]
-->
### 📋 Project Overview
Designed and executed an end-to-end automated testing framework for a mock e-commerce platform. The objective was to eliminate repetitive manual regression testing for the checkout funnel, which reduced release regression testing time by **60%**.

### 🛠️ Tech Stack Used
* **Framework:** Playwright (TypeScript)
* **Design Pattern:** Page Object Model (POM)
* **CI/CD:** GitHub Actions for automated nightly test execution
* **Reporting:** Mochawesome reports integrated with Slack alerts

### 🔍 Key Capabilities & Test Coverage
* **UI Testing:** Validated full user journeys: User Registration ➡️ Product Search ➡️ Add to Cart ➡️ Payment Checkout.
* **API Testing:** Automated response verification for authentication and payment gateway endpoints using Cypress API commands.
* **Data-Driven Testing:** Leveraged JSON fixtures to test multiple edge-case user inputs and invalid coupon scenarios.

### 🐛 Bug Highlight & Resolution
During stress testing of the cart module, I uncovered a **race condition bug** where rapidly clicking the "Add to Cart" button duplicated items and corrupted the session payload. 
* **Impact:** High. Could cause financial discrepancy and poor UX.
* **Action:** Logged a detailed bug report in Jira with reproducible steps, logs, and a video recording. Collaborated closely with the frontend developer to verify the fix via a patch branch.

---

## 📑 Technical Project Case Studies

### 1. REST API Test Automation Framework
* **Tools:** Postman, Newman, JavaScript
* **Summary:** Developed a structured regression suite for a RESTful banking API. Implemented dynamic environment variables, pre-request script authentication tokens, and JavaScript assertions to validate status codes, schema compliance, and response times under 200ms.

### 2. Manual Testing & Exploratory Testing Artifacts
* **Tools:** JIRA, Confluence, Xray / Zephyr
* **Summary:** Conducted exhaustive cross-browser exploratory testing for a responsive SaaS dashboard. Created a robust, reusable master test plan, executed over 150 test cases, and mapped out an extensive traceability matrix linking requirements to test artifacts.
* **Artifacts Included:** [Link to Sample Test Plan](https://github.com/mark-qa2011/QA-Templates/blob/main/TestPlan-template.md) | [Link to Sample Bug Report Template](https://github.com/mark-qa2011/Bug-ticket-template/blob/main/bug-template.md)

---

## ⚙️ CI/CD & DevOps Integration
I believe QA shouldn't be a bottleneck at the end of a sprint. I integrate my tests directly into the developer workflow:
* **Nightly Runs:** Configured pipeline workflows to trigger automated regression suites every midnight against the staging environment.
* **Pull Request Gates:** Configured smoke test workflows that must pass before any developer's Pull Request can be merged into the `main` branch.

---

## 📈 Impact Metrics
* **100+** Bugs identified and tracked to resolution before production releases.
* **85%** Test coverage achieved on critical business flows.
* **Zero** Critical/Blocker bugs leaked to production over the last 3 major releases.

# 🧪 QA_Testing_Mastery

**QA_Testing_Mastery** is a comprehensive project designed to master **Software Quality Assurance (SQA)** techniques, focusing primarily on **manual testing**. This project simulates real-world testing scenarios to ensure **software reliability**, **performance**, and **user satisfaction**.

## 📋 Project Overview

The project aims to showcase expertise in **manual software testing** by simulating various software application testing scenarios. By creating detailed test cases, tracking bugs, and evaluating performance, this project emphasizes the importance of delivering **high-quality software** through efficient testing processes.

### 🔑 Key Features:
- **Manual testing** for functionality, regression, and usability.
- Creation of detailed **test cases** to cover multiple application modules.
- Comprehensive **bug tracking** and reporting.
- **Performance testing** using industry-standard tools.
- Real-world test scenarios to ensure **software stability** and **user satisfaction**.

## 🛠️ Tools & Technologies

- **Manual Testing**: For verifying application features and performance.
- **Jira**: For tracking bugs, assigning priorities, and managing testing tasks.
- **Postman**: For testing APIs and validating their responses.
- **Google Sheets/Excel**: For documenting test cases and results.

## 📂 Project Structure

```bash
QA_Testing_Mastery/
│
├── Test_Cases/                   # Organized test cases for various features
│   └── User_Authentication_TestCases.xlsx
│   └── Payment_Module_TestCases.xlsx
│
├── Bug_Reports/                  # Detailed reports on bugs found during testing
│   └── User_Login_Bug_Report.pdf
│   └── Payment_Failure_Bug_Report.pdf
│
├── API_Testing/                  # API testing results using Postman
│   └── Postman_Collection.json
│   └── API_Testing_Report.pdf
│
├── Performance_Reports/          # Performance evaluation reports
│   └── Performance_Testing_Report.pdf
│
├── README.md                     # Project overview and documentation
```

## 📐 Testing Process

1. **Test Case Development**:  
   Test cases are created based on the application’s requirements, covering critical modules like **user authentication** and **payment gateways**. Each test case details the expected behavior and steps for reproduction.

2. **Manual Testing**:  
   Manual testing is performed to evaluate the **functionality**, **usability**, and **performance** of the application. Test results are logged, and deviations from expected outcomes are recorded.

3. **Bug Reporting**:  
   Bugs are reported using **Jira**, and each issue is thoroughly documented, including severity, priority, steps to reproduce, and visual evidence (e.g., screenshots or videos).

4. **Performance Testing**:  
   Performance tests are conducted to assess system stability under varying load conditions, with performance metrics logged and analyzed.

5. **API Testing**:  
   Using **Postman**, APIs are tested for correctness, response time, and data integrity. This includes validating API requests and responses for key modules such as user registration and payment processing.

## 🐞 Sample Bug Report

**Bug Title**: Login Button Not Responsive on Mobile  
**Severity**: High  
**Priority**: Critical  

**Steps to Reproduce**:
1. Open the app on a mobile device.
2. Navigate to the login page.
3. Enter valid credentials and click the login button.
4. Observe that the login button is not responsive.

**Expected Result**: The login button should respond and log the user into the system.  
**Actual Result**: The button remains unresponsive, preventing login.

**Resolution**: The issue was replicated across devices and reported to the development team.

## 🚀 API Testing Process

**Postman** is used to test API endpoints, validating that responses are correct and meet expected performance standards. API testing includes verifying:
- **User authentication** via API.
- **Payment processing** and error handling.
- Data validation and consistency across responses.

## 🔧 Performance Evaluation

The application’s performance is evaluated under various loads and conditions using **manual testing methods**. **Performance testing reports** track response times, load-handling capacity, and system stability during stress testing.

## 🔗 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/AreejPanhwer/QA_Testing_Mastery
   ```

2. Navigate to the **Test_Cases** folder to explore detailed test case documentation.
3. Review the **Bug_Reports** for identified issues and their resolutions.
4. For **API Testing**, import the Postman collection available in the **API_Testing** folder and run tests.

## 🤝 Contributions

We welcome contributions to improve this project! You can:
- Submit additional test cases.
- Report bugs or issues.
- Suggest enhancements to the testing process.

## 📜 License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.

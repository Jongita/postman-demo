# API Testing with Postman and Newman

<br>

## 🌟 About

This project contains Postman collections for testing the [Automation Exercise](https://www.automationexercise.com/) web application. This collection performs automated tests to ensure that the API responses meet the expected results. The tests check for correct status codes, proper response structures, and content validation.

## 🎯 Project Features

-   **Retrieve Product Lists:** Fetch all product listings from the API.
-   **Retrieve Brand Lists:** Fetch all brands available on the website.
-   **Search Products:** Search for products by a specific keyword.
-   **Create User Account:** Automate the creation of new user accounts.
-   **Delete User Account:** Automate the deletion of existing user accounts.
-   **Error Handling:** Test unsupported HTTP methods like POST and PUT on certain endpoints

## 🧪 Test Cases

1. **Get All Products List** Retrieves the list of all products.
2. **POST To All Products List** Tests unsupported POST request on products.
3. **Get All Brands List** Retrieves the list of all brands.
4. **PUT To All Brands List** Tests unsupported PUT request on brands.
5. **POST To Search Product** Searches for products based on a keyword.
6. **POST To Create/Register User Account** Creates a new user account.
7. **DELETE User Account** Deletes an existing user account.

## 🧰 Getting Started

### 💻 Prerequisites

To run this project locally, you need to have the following software installed:

-   **Node.js** - Download and install from [nodejs.org](https://nodejs.org)
-   **Git** - Download and install from [git-scm.com](https://git-scm.com)
-   **Postman** - Download and install from [postman](https://www.postman.com/downloads/)

### 🏃 Run Locally

Would you like to run this project locally? Open your terminal and follow these steps:

1. Clone the repo
    ```sh
    git clone https://github.com/Jongita/postman-demo
    cd postman-demo
    ```
2. Install NPM packages
    ```sh
    npm install
    ```
3. Running Tests with Newman
    ```sh
    npm run test
    ```

## 🎓 Viewing Test Reports

Once the tests are executed in a CI/CD environment (e.g., GitHub Actions), the HTML report is generated and saved in the testResults folder. You can view the test results by downloading the report from the CI artifact section.

## 🎉 Conclusion

This Postman collection provides a comprehensive set of API requests and tests to validate the functionality of AutomationExercise's e-commerce platform. It checks for the correctness of API responses, ensuring they meet expected standards and formats. The tests are automated and reusable, making it easy to integrate with CI/CD pipelines.

## 🎅 Authors

Jongita: [Profile](https://github.com/jongita)

## ⚠️ License

Distributed under the MIT License. See LICENSE.txt for more information.

## 🔗 Other resources

No other resources.

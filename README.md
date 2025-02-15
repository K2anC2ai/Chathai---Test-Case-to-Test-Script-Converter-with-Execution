# Chathai - Test Case to Test Script Converter

**Chathai** is a CLI tool that converts test cases from an Excel file into test scripts for popular testing frameworks like Cypress and Playwright.

## 🚀 Installation
Install globally using npm:
```sh
npm install -g chathai
```

## 🛠 Usage
Run the CLI to open the UI:
```sh
npx chathai start
```

### How It Works
1. Select a `.xlsx` file containing test cases.
2. Choose the testing framework (Cypress, Playwright).
3. The system will generate test scripts based on the selected framework.

## 📦 Features
- 📂 **Supports Excel (.xlsx) test case format**
- 🔄 **Converts test cases into Cypress/Playwright scripts**
- 🖥️ **Simple UI for selecting files and frameworks**
- ⚡ **Quick and easy automation script generation**

## 📜 Example Test Case Format
| Test Case ID | Description        | URL         | Selector     | Action | Value  |
|-------------|------------------|------------|-------------|--------|--------|
| TC001       | Login to website | https://example.com | #username | type   | user123 |
| TC002       | Click submit     | N/A        | #submitBtn  | click  | N/A    |

## 🌍 Contributing
Feel free to contribute by opening issues or pull requests!

📌 **GitHub Repository:** [GitHub.com/your-username/chathai](https://github.com/your-username/chathai)


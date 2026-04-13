# 🧪 Unit & Component Testing Suite

## 📌 Project Overview
This project demonstrates **Unit Testing** and **Component Testing** in a React/Next.js application using **Jest** and **React Testing Library (RTL)**.

The goal is to ensure that UI components are reliable, bug-free, and production-ready through automated testing—just like in enterprise-level applications.

---

## 🌐 Live Demo
🔗 https://unit-component-testing.vercel.app/

---

## 🎯 Objectives
- Implement automated testing for UI components
- Ensure components render correctly
- Validate user interactions
- Achieve minimum **70% test coverage**

---

## 🚀 Features

### ✅ Level 1 (Beginner)
- Installed and configured:
  - Jest
  - React Testing Library (RTL)
- Created unit tests for:
  - Button Component
  - Input Component
  - Card Component
- Verified:
  - Component renders without crashing
  - Correct text is displayed via props

---

### ⚙️ Level 2 (Intermediate)
- Implemented **interaction testing**
- Used:
  - `userEvent`
  - `fireEvent`
- Tested:
  - Button click (e.g., increment counter)
  - Input field typing behavior
- Ensured UI updates correctly based on user actions

---

### 🚀 Level 3 (Advanced)
- Implemented **API mocking**
  - Mocked `fetch` / `axios` calls
  - Prevented real API calls during tests
- Generated **Test Coverage Report**
  ```bash
  npm test -- --coverage

  Achieved 70%+ test coverage
🛠️ Tech Stack
React / Next.js
Jest
React Testing Library (RTL)
JavaScript (ES6+)
📂 Project Structure

├── components/
│   ├── Button.jsx
│   ├── Input.jsx
│   ├── Card.jsx
│
├── **tests**/
│   ├── Button.test.js
│   ├── Input.test.js
│   ├── Card.test.js
│
├── jest.config.js
├── package.json

⚡ Getting Started
1. Install Dependencies
npm install
2. Run Tests
npm test
3. Run Coverage Report
npm test -- --coverage
🧠 Key Concepts Covered
Unit Testing
Component Testing
Test-Driven Development (TDD) basics
DOM Testing with RTL
User interaction simulation
API mocking
Code coverage analysis
📊 Test Coverage
Minimum target: 70%
Includes:
Components
Interaction logic
API handling
📸 Screenshots

(Add screenshots of test results and coverage report here)

💡 Future Improvements
Add integration tests
Add end-to-end testing (Cypress / Playwright)
Increase test coverage beyond 90%
Add CI/CD pipeline for automated testing
🤝 Contributing

Feel free to fork and improve this project.

📄 License

This project is open-source and available under the MIT License

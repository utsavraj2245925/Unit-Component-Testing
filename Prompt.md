# 🧠 Project Prompt – Unit & Component Testing Suite

## 🎯 Objective
The objective of this project is to implement **Unit Testing** and **Component Testing** in a React/Next.js application using **Jest** and **React Testing Library (RTL)**.

The goal is to ensure that UI components are reliable, testable, and production-ready by validating their behavior through automated tests.

---

## 🌐 Live Deployment
🔗 https://unit-component-testing.vercel.app/

---

## 📌 Background
In enterprise-level applications, code cannot be deployed to production without proper test coverage. Even small UI changes can introduce unexpected bugs.

To prevent this, developers write automated tests that:
- Validate component rendering
- Ensure correct data flow via props
- Simulate real user interactions
- Prevent regressions

---

## 🧩 Project Requirements

### 🔰 Level 1 (Beginner)
- Install and configure:
  - Jest
  - React Testing Library (RTL)
- Write unit tests for at least **3 UI components**:
  - Button
  - Input Field
  - Card
- Test cases must verify:
  - Component renders without crashing
  - Correct text/content is displayed via props

---

### ⚙️ Level 2 (Intermediate)
- Implement **interaction testing**
- Use:
  - `userEvent`
  - `fireEvent`
- Test real user behavior:
  - Button click updates UI (e.g., counter increment)
  - Input typing updates value
- Ensure DOM updates correctly after events

---

### 🚀 Level 3 (Advanced)
- Implement **API mocking**
  - Mock `fetch` or `axios` calls
  - Avoid real network requests during testing
- Test components that depend on external data
- Generate **test coverage report**:
  ```bash
  npm test -- --coverage

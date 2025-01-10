# bTaskee challenge

## Project Overview
The goal is to build a **Task Management app** with the following features:
1. **Task List View**: Display a list of tasks.
2. **Add Task**: Allow users to add a new task.
3. **Mark Task as Completed**: Allow users to toggle the completion status of a task.
4. **Delete Task**: Allow users to remove a task.
5. **Search Tasks**: Include a search bar to filter tasks by title.
6. **Persist Data**: Store tasks in the browser's local storage.

---

## Deliverables
You are expected to submit:
1. [Must have] Use React or any framework based on it, use Typescript, dependency packages is latest version
2. [Must have] Unit tests using Jest and React Testing Library.
3. [Nice to have] End-to-end (E2E) tests using Cypress or Playwright.
4. [Must have] A **README.md** file explaining:
   - How to set up and run the project.
   - How to run tests.
   - Any design decisions or assumptions made.

---

## Core Expectations
The implementation will be evaluated based on:
1. **Clean Code**: Modular, reusable components, proper TypeScript usage.
2. **Testing**: Coverage of unit and E2E tests for critical features.
3. **Functionality**: Accurate implementation of the specified features.
4. **Documentation**: Clear and concise setup instructions.

---

## TODO List for the Challenge

### Step 1: Project Setup (0.5 Hour)
- Fork from this repository.
- Create a React project using Vite, Create React App, or Next.js.
- Configure TypeScript for type safety.
- Install dependencies:
  - **Testing libraries**: Jest, React Testing Library.
  - **E2E testing**: Cypress or Playwright.
- Set up ESLint and Prettier for clean code enforcement.
- Create a pull request from your fork into this repository.
---

### Step 2: Implement Core Features (4 Hours)
1. **Task List Component**:
   - Display a list of tasks with title, status (completed/incomplete), and delete button.
   - Use React state to manage tasks.

2. **Add Task Component**:
   - Provide an input field and a button to add a new task.
   - Validate input (e.g., prevent empty task titles).

3. **Mark Task as Completed**:
   - Allow users to toggle the completion status of a task.

4. **Delete Task**:
   - Implement a button to delete a task.

5. **Search Tasks**:
   - Add a search bar to filter tasks by title.

6. **Persist Data**:
   - Save tasks to local storage and retrieve them on page reload.

---

### Step 3: Write Unit Tests (2 Hours)
- Use Jest and React Testing Library to test:
  - Components
  - Customhook
  - Functions: Search, Add, Delete, ...
- Ensure full of coverage score

---

### Step 4: Write E2E Tests (1 Hour)
- Use Cypress or Playwright to test:
  - Adding a task and verifying it appears in the list.
  - Marking a task as completed and verifying its state.
  - Deleting a task and ensuring it is removed.
  - Searching tasks and verifying the filtered results.

---

### Step 5: Final Touches and Documentation (0.5 Hour)
- **Code Review by yourself**: Ensure clean code, proper TypeScript types, and React best practices.
- **Documentation**:
  - Add setup instructions (e.g., installing dependencies, running the app, and running tests).
  - Provide a brief explanation of your design decisions and technologies used.

---

**Ask our if you have any problems, or questions about this challenge. Fighting!**

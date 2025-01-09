# bTaskee challenge

## Project Overview
The goal is to build a **Task Management App** with the following features:
1. **Task List View**: Display a list of tasks.
2. **Add Task**: Allow users to add a new task.
3. **Mark Task as Completed**: Allow users to toggle the completion status of a task.
4. **Delete Task**: Allow users to remove a task.
5. **Search Tasks**: Include a search bar to filter tasks by title.
6. **Persist Data**: Store tasks in the browser's local storage.

---

## Deliverables
You are expected to submit:
1. A functional React app.
2. Unit tests for core components using Jest and React Testing Library.
3. End-to-End (E2E) tests using Cypress or Playwright.
4. A **README.md** file explaining:
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
5. **Attention to Detail**: Edge cases, responsive UI, and user-friendly design.

---

## TODO List for the Challenge

### Step 1: Project Setup (1 Hour)
- Create a React project using Vite, Create React App, or Next.js.
- Configure TypeScript for type safety.
- Install dependencies:
  - **Testing libraries**: Jest, React Testing Library.
  - **E2E testing**: Cypress or Playwright.
- Set up ESLint and Prettier for clean code enforcement.

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
   - Add a search bar to filter tasks by title in real-time.

6. **Persist Data**:
   - Save tasks to local storage and retrieve them on page reload.

---

### Step 3: Write Unit Tests (1.5 Hours)
- Use Jest and React Testing Library to test:
  - Task addition functionality.
  - Task completion toggle.
  - Task deletion.
  - Search functionality.
- Include at least one test to ensure components render properly with props.

---

### Step 4: Write E2E Tests (1 Hour)
- Use Cypress or Playwright to test:
  - Adding a task and verifying it appears in the list.
  - Marking a task as completed and verifying its state.
  - Deleting a task and ensuring it is removed.
  - Searching tasks and verifying the filtered results.

---

### Step 5: Final Touches and Documentation (0.5 Hour)
- **Code Review**: Ensure clean code, proper TypeScript types, and React best practices.
- **Documentation**:
  - Add setup instructions (e.g., installing dependencies, running the app, and running tests).
  - Provide a brief explanation of your design decisions and technologies used.

---

## Evaluation Criteria
1. **Code Quality**:
   - Clean, modular, and reusable components.
   - Proper use of TypeScript for type safety.
2. **Testing**:
   - Sufficient unit test coverage.
   - Functional E2E tests for core flows.
3. **Functionality**:
   - All features implemented accurately.
   - Tasks persist across page reloads.
4. **Documentation**:
   - Clear setup instructions in the README file.
5. **Attention to Detail**:
   - Edge cases handled (e.g., empty tasks, duplicate tasks).
   - User-friendly and responsive UI.

---

## Extra Credit (Optional Tasks)
1. **Dark Mode Toggle**:
   - Add a dark mode toggle using React Context or simple state.
2. **Task Prioritization**:
   - Allow users to set task priority (e.g., high, medium, low) and sort tasks accordingly.

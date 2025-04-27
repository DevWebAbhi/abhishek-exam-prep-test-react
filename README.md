# 📚 React Assignment: Student Management System

## Objective

Build a simple **Student Management React Application** using **React Router DOM**.  
The application should allow users to **view**, **add**, **edit**, and **delete** student records.

---

## Data Structure

The student data will be stored in a `data.json` file in the following format:

```json
[
  {
    "id": 1,
    "name": "Aarav Mehta",
    "age": 16,
    "gender": "Male",
    "grade": "10",
    "email": "aarav.mehta@example.com"
  }
]
```

Each student will have the following fields:
- `id`: Unique ID (number)
- `name`: Name of the student (string)
- `age`: Age of the student (number)
- `gender`: Gender (string)
- `grade`: Grade/Class (string)
- `email`: Email address (string)

---

## Important Note ⚡

- You must **import the student data** from `data.json` into your React component using the `import` statement.
- Set this imported data into a React state (`useState`) and manage all operations (view, add, edit, delete) using the state.

---

## Pages to Build

### 1. Homepage (Homepage.jsx)

- Fetch and display the list of students from the state (which is initialized using `data.json`).
- For each student, display all details:
  - Name
  - Age
  - Gender
  - Grade
  - Email
- Each student card must have:
  - An **Edit** button
  - A **Delete** button

- **Delete Functionality**:
  - On clicking the Delete button, the student should be removed from the state.
  - The updated list should be shown immediately.

- **Edit Functionality**:
  - On clicking the Edit button for a particular student:
    - Input fields should appear **inside the student card**.
    - Each field (name, age, gender, grade, email) must become editable.
    - After editing, provide a **Save** button to update the details.

### 2. Add Student Page (Form.jsx)

- Create a form to add a new student.
- The form should include fields for:
  - Name
  - Age
  - Gender
  - Grade
  - Email
- On submitting the form:
  - A new student should be added to the existing list (state).
  - Redirect the user to the Homepage to see the updated list.

---

## Navbar (Navbar.jsx)

- Create a Navbar with links to:
  - Homepage (`/`)
  - Add Student (`/add-student`)
- Use **React Router DOM** `<Link>` for navigation.

---

## Routing (App.js)

- Set up routing using **React Router DOM**.
- Configure the following routes:
  - `/` → `Homepage.jsx`
  - `/add-student` → `Form.jsx`
- The Navbar should be visible on all pages.

---

## Functionality Summary

- Show all students on the Homepage.
- Add a new student from Form.jsx.
- Delete an existing student from the Homepage.
- Edit a student's details directly inside their card.
- Update the UI immediately after any operation.

---

## Bonus (Optional)

- Add basic form validation (no empty fields allowed).
- Add a confirmation popup before deleting a student.
- Improve the design using simple CSS or any UI framework (like TailwindCSS or Bootstrap).

---

## Submission Guidelines

- Upload your full project to **GitHub**.
- Share the **GitHub repository link**.
- Ensure the application runs without errors before submitting.

---

## Important Notes

- Use only **functional components** and **React Hooks** (`useState`, `useEffect`).
- Manage the student list using **React state**.
- Use **React Router DOM** for page navigation.
- Import initial data from `data.json`.
- Keep your code **clean**, **organized**, and **well-commented**.

---

# 🚀 Good Luck and Happy Coding!

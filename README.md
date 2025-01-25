# Software Engineer - Technical Test

## Overview

The purpose of this test is to evaluate the candidate's ability to work with React, manage state effectively, integrate external APIs, and create clean, user-friendly interfaces. The test includes tasks involving UI design, data manipulation, form validation, and API integration.

---

## Instructions

You are tasked with creating a React-based application for managing users. The application must include the following features:

---

### 1. **User Table**

- Display a table of users with the following columns:
  - **Name**
  - **Email**
  - **Phone Number**
  - **Role** (e.g., Admin, User)
  - **Status** (e.g., Active, Inactive)
  - **Actions**: Edit and Delete buttons
- The table should:
  - Display 50 users with randomly generated data.
  - Allow filtering by:
    - **Role** and **Status** (dropdowns).
    - **Search** by partial matches in Name or Email.
  - Support sorting by any column (ascending/descending).
  - Handle large datasets efficiently (e.g., pagination or virtualization).

---

### 2. **Add User Form**

- Create a form to add a new user to the table. The form should include the following fields:
  - **First Name**
  - **Last Name**
  - **Middle Name** (optional)
  - **Email** (validate format)
  - **Phone Number** (validate format)
  - **Role** (dropdown with "Admin" and "User" as options)
  - **Address**:
    - Option 1: Use a map to select a location. Autofill the fields for:
      - Street
      - Number
      - Neighborhood
      - City
      - Postal Code
    - Option 2: Provide address details manually, then use the data to find and display the corresponding coordinates on the map.
  - **Profile Picture**:
    - Allow the user to upload an image file (e.g., `.jpg`, `.png`).
    - Upon submission, upload the image to the ImgBB API and save the returned image URL in the user data.
- **Validation**:
  - All fields except Middle Name must be required.
  - Display appropriate error messages for invalid input.
  - Ensure valid email and phone formats.

---

### 3. **Edit User**

- Clicking the "Edit" button in the table should allow the user to update the selected user’s information.
- Pre-fill the form with the existing user data.
- Validate the updated data before saving.

---

### 4. **Delete User**

- Clicking the "Delete" button should prompt a confirmation dialog.
- Upon confirmation, remove the user from the table.

---

### 5. **Bonus Features** (Optional)

- Use a design tool like Figma to mock up the UI before implementation.
- Implement unit tests for key components (e.g., table, form).
- Style the application using a modern UI framework (e.g., Material-UI, TailwindCSS).
- Use TypeScript for type safety.
- Persist the user data in local storage or an API (mock or real).
- Optimize the app for mobile devices (responsive design).
- **Global State Management**: Use a state management library like Redux, Recoil, or Zustand to handle user data globally.
- Include drag-and-drop functionality to reorder users in the table.
- Provide visual feedback (e.g., loaders) for async actions like uploading images or saving user data.

---

## Deliverables

1. **Source Code**:
   - A GitHub repository containing the React project.
   - Include a clear folder structure and comments.
2. **Figma Design** (Optional):
   - Share a link to the UI mockup if created.
3. **README.md**:
   - How to set up and run the project.
   - A brief explanation of your implementation and any decisions made.
   - List of libraries or frameworks used.
   - Any challenges faced and how they were overcome.

---

## Evaluation Criteria

- **Functionality**: Does the app meet the requirements?
- **Code Quality**: Is the code clean, readable, and well-structured?
- **UI/UX Design**: Is the interface intuitive and visually appealing?
- **Problem-Solving**: How well were challenges addressed?
- **Bonus Features**: Extra points for implementing optional tasks.

---

## How to Submit

1. Push your code to a public GitHub repository.
2. Share the repository link and any additional files (e.g., Figma link) via email.

---

**API Reference for ImgBB**:
- [ImgBB API Documentation](https://api.imgbb.com/)
- You will need an API key to use ImgBB. Create a free account and obtain your key from the ImgBB dashboard.

Good luck! We look forward to reviewing your work!

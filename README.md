# CSE224 CA 2
This project is a Registration Form Android application built using Jetpack Compose.
It demonstrates form input handling, state management, validation logic, radio button selection, and Snackbar-based user feedback.

The app satisfies a typical exam-style problem statement involving UI components, validation rules, and conditional feedback.

## Problem Statement
- The application contains:
  - Three input fields:
    - Full Name
    - Email ID
    - Phone Number
  - A radio button group for selecting the registration type:
    - Student
    - Professional
  - A Register button

## Showing Snackbar
- If any input field is empty or no registration type is selected, show:
```bash
Please fill all fields and select a registration type.
```

- If all fields are filled and a registration type is selected, show:
```bash
Registration completed successfully.
```

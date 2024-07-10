---
## Flask Application Design for Quizzing Web App

### HTML Files
- **index.html**:
    - Main page of the application that displays the questions for the day.
    - Will include a button to generate new questions.
- **question_form.html**:
    - Form to create new questions.
    - Contains fields for question text and answer choices.
- **results.html**:
    - Page to display the results after answering the questions.
    - Contains the correct answers and user's choices.

### Routes
- **`/`**:
    - Route for the home page (`index.html`).
- **`/generate`**:
    - Route to generate 5 new questions and display them on the home page.
- **`/add`**:
    - Route to add a new question using the form in `question_form.html`.
- **`/check`**:
    - Route to check the user's answers and display the results in `results.html`.
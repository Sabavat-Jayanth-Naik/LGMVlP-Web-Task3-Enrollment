# LGMVlP-Web-Task3-Enrollment
Certainly! The provided code implements a basic student enrollment form using HTML, CSS, and JavaScript. Let's break down each part and describe their functionalities:
![image](https://github.com/Sabavat-Jayanth-Naik/LGMVlP-Web-Task3-Enrollment/assets/130920035/a013d1ab-05aa-44a0-926f-5962fc493549)

1. **HTML (index.html):**
   - The HTML file defines the structure of the webpage.
   - It includes a form with several input fields for collecting student information.
   - The form has fields for Full Name, Email, Date of Birth, and Course selection.
   - Upon submission, the form data will be processed using JavaScript.
   - A `<script>` tag at the end of the body references the JavaScript file (`script.js`) for adding interactivity.

2. **CSS (styles.css):**
   - The CSS file styles the appearance of the webpage and the form elements.
   - The background color, font family, and spacing are defined for the overall page.
   - The form container is centered on the page, with padding and a shadow effect to give it a clean look.
   - The form elements (`input`, `select`, `button`) are styled to have consistent padding, border, and background.
   - The button changes color on hover to provide visual feedback.

3. **JavaScript (script.js):**
   - The JavaScript code enhances the form's functionality and interactivity.
   - The `DOMContentLoaded` event listener ensures that the JavaScript code executes after the HTML content is loaded.
   - An event listener is added to the form's `submit` event. When the form is submitted:
       - The event's default behavior (submitting and reloading the page) is prevented using `event.preventDefault()`.
       - The values entered by the user in the form fields are extracted.
       - An alert is displayed, showing the submitted information along with a confirmation message.
       - The `form.reset()` method is called to clear the form fields after submission.

Overall, this code provides a user-friendly enrollment form where students can input their details, and upon submission, they receive a confirmation message with the information they entered. This is a simple example that can serve as a starting point for more complex forms that might involve data validation, backend processing, or user authentication. You can further customize the styles, add validation logic, and connect the form to a backend server to store the submitted data.

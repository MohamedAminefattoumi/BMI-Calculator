# BMI-Calculator
This project is a BMI Calculator web application that allows users to calculate their Body Mass Index (BMI) based on their weight and height. The application is designed with a modern and professional user interface, ensuring a smooth and responsive experience.

Key Features:
User Input:

Users are prompted to enter their weight (in kilograms) and height (in meters) through input fields.
The form provides basic validation to ensure the input values fall within reasonable ranges (e.g., weight between 20 and 200 kg, height between 1 and 3 meters).
API Communication:

The application communicates with a FastAPI backend that calculates the BMI based on the input weight and height.
The backend returns the BMI value and a message indicating the user's health status based on the BMI:
Underweight
Normal weight
Overweight
Obesity
Result Display:

After the user submits the form, the BMI result is displayed with a corresponding message.
The result is styled differently based on the outcome (e.g., green for a healthy BMI, orange for overweight, red for underweight or obesity).
The results are shown in a stylish box, which also provides feedback in case of errors, such as invalid input or issues with the API communication.
Responsive Design:

The interface is designed to be responsive, ensuring that the application works well on both desktop and mobile devices.
The background is a beautiful gradient (or solid color, based on the choice) to create an attractive visual design.
Professional Look:

The page is designed using HTML and CSS for layout and styling, and it incorporates Google Fonts for better typography.
The form uses modern input elements with clear labels and an intuitive button for submission.
API Error Handling:

If there is an error communicating with the API, the user receives an error message, ensuring that they are informed when something goes wrong.
Technologies Used:
Frontend: HTML, CSS (with responsive design), JavaScript (for handling form submission and API communication)
Backend: FastAPI (for calculating BMI and serving data to the frontend)
API Interaction: Fetch API (for sending HTTP requests to the backend and handling responses)
Application Flow:
The user enters their weight and height.
When the user submits the form, a request is sent to the FastAPI server, which calculates the BMI.
The server responds with the calculated BMI and a health message.
The frontend displays the result in a styled box with appropriate feedback (error or success).
This project demonstrates how to integrate frontend design with backend API services to create an interactive web application. It provides users with an easy-to-use BMI calculator with a clean, modern design and clear, helpful feedback.

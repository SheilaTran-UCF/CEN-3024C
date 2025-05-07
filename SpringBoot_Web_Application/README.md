# CEN-3024C

# Spring Boot Web Application - Hello World & User Input Form

This Java project is a **Spring Boot web application** with two main parts:
1. **Part 01**: A simple Spring Boot application that displays a centered, red-colored "Hello World!" message on a webpage.
2. **Part 02**: A form-based web application that accepts user input (Student ID, Date, and Message), validates the data, and displays the formatted results back to the user.

## Technologies Used
- **Java** – Programming language used for the project.
- **Spring Boot** – Framework used for building the web application.
- **Thymeleaf** – Template engine for rendering HTML content.
- **Maven** – Build tool for managing dependencies and building the project.

## Part 01: Hello World Application
This part of the project is a basic Spring Boot application that runs a local web server and displays a "Hello World!" message on a webpage. The message is centered and displayed in red using simple HTML and CSS.

### Features:
- Starts a local server on port `8080`.
- Displays a "Hello World!" message on the home page.

## Part 02: User Input Form
This part of the project creates a form where the user can input:
- **Student ID** (String)
- **Date** (month, day, year)
- **Message** (String)

Once the user submits the form, the input is validated, and the formatted results are displayed on a results page.

### Features:
- Accepts user input through a form.
- Validates input for correct formatting.
- Displays the input back to the user in a formatted manner.

## How to Run

### Prerequisites:
- Java 11 or higher installed.
- Maven installed (for dependency management).

### Steps:
1. Clone or download this repository to your local machine.
2. Navigate to the project folder in the terminal.
3. Run the following command to start the application:
    ```bash
    mvn spring-boot:run
    ```
4. Once the application is running, open your web browser and go to [http://localhost:8080](http://localhost:8080).
5. You will see the "Hello World!" message for **Part 01**.
6. Navigate to the user input form and fill out the fields for **Part 02**.

## Example Usage

### Part 01 (Hello World):
1. Open [http://localhost:8080](http://localhost:8080) in your browser.
2. You should see a centered "Hello World!" message displayed in red.

### Part 02 (User Input Form):
1. On the webpage, navigate to the input form.
2. Enter the following:
    - **Student ID**: `12345`
    - **Date**: `05/07/2025`
    - **Message**: `This is my first Spring Boot app!`
3. Submit the form.
4. The results page will display the formatted information you entered.

## Known Issues
- The date input might not handle leap years correctly in its validation (if applicable).
- Ensure all fields are filled in properly; there may be missing error handling for incomplete forms.

## License
This project is licensed under the MIT License – see the [LICENSE](MIT LICENSE) file for details.

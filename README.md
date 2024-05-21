# Splitwise Application Web Project

Welcome to the comprehensive Splitwise Application Web Project. This project is designed to deepen your understanding of full-stack application development using Spring Boot. You will build an application inspired by popular expense-sharing platforms, utilizing Java, Spring Boot, Thymeleaf templates, and modern web technologies to enhance your software development skills.

## Project Structure and Components

### Source Directory (`src/main/java/co/newtonschool/splitwise`)

- **controller**: Manages HTTP requests with `ExpenseController`, `UserController`, and `HomeController`.
- **model**: Defines data structures with `Expense`, `User`, and `UserExpense`.
- **repository**: Handles database operations via `UserRepository` and `ExpenseRepository`.
- **service**: Implements business logic in `ExpenseServiceImpl` and `UserServiceimpl`.
- **request**: Captures web request data with classes like `ExpenseRequest` and `UserRequest`.
- **response**: Formats data sent back to clients with `ExpenseResponse`, `UserResponse`, etc.

### Templates Directory (`src/main/resources/templates`)

Contains Thymeleaf HTML templates for the UI:

- `add-expense.html`
- `create-user.html`
- `expense.html`
- `expense-list.html`
- `home.html`
- `navbar.html`
- `user.html`
- `user-list.html`

## Project Objectives

Develop a robust backend in Java using Spring Boot, alongside a dynamic frontend using Thymeleaf templates. This app should enable efficient management of shared expenses, mimicking real-world financial interactions among users.

## Development Requirements

### Java Class Structure

- **Core Models**: `Expense`, `User`, `UserExpense`.
- **Service Classes**: Implement vital services in `ExpenseService` and `UserService`.

### Functionalities to Implement

- **User Management**: Implement user registration and login processes.
- **Expense Management**: Allow adding, updating, and deleting expenses.
- **Expense Sharing**: Enable splitting expenses among users with balance tracking and settlement functionalities.
- **Reporting**: Provide detailed expense reports and user balance overviews.

### Enhancements and Customization

- Extend the functionality of Thymeleaf templates.
- Refine UI/UX for enhanced user interaction and responsive design.
- Add innovative features like payment reminders or expense analytics.

## To Do's

### Models

- `Expense`
- `User`
- `UserExpense`

### Responses

- `ExpenseResponse`
- `ExpenseResponseList`
- `ExpenseUserDetail`
- `ExpenseUserResponse` (already provided)
- `GenericResponse` (already provided)
- `UserExpenseDetail`
- `UserExpenseResponse`
- `UserResponse`
- `UserResponseList`

## Additional Project Insights

- **Encourage Creativity**: Incorporate unique features that improve usability and functionality.
- **Focus on Documentation**: Document all code and functionalities thoroughly for easy maintenance and clarity.
- **Practice Version Control**: Utilize Git for version control with regular commits documenting progress.

## Submission Protocols

- **Complete Project Folder**: Submit all source codes and web files.
- **README.md**: Include an architectural blueprint, setup instructions, and a summary of additional features.

## Evaluation Criteria

- **Functionality**: How effectively the application operates.
- **Code Quality**: Organization, structure, and documentation of the code.
- **Innovative Approach**: Creativity in new features or project elements.
- **UI/UX Design**: Application’s front-end intuitiveness, aesthetics, and user-friendliness.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
cd splitwise-application
mvn clean install
mvn spring-boot:run
Open your web browser and go to http://localhost:8080.



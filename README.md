Description of LoginForm Component
The LoginForm component is a simple React-based login form that uses the useState hook for managing form state and validation errors.

Functionality:
State Management:

formData: Stores the values of username and password fields.

errors: Stores validation error messages.

Event Handlers:

handleChange: Updates formData state when the user types in the input fields.

handleSubmit: Validates input fields when the form is submitted.

Checks if the username is empty.

Checks if the password is empty.

If validation fails, error messages are displayed.

If validation passes, an alert message is shown.

Rendering:

Displays input fields for username and password.

Displays error messages in red if validation fails.

Includes a submit button to trigger form submission.

Key Features:
Basic form validation.

Controlled components with useState.

User-friendly error messages.

Simple alert-based login success message (can be extended to integrate authentication).

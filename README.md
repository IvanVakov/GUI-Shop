# GUI-Shop
This is a console application -Gui Shop from SoftUni Advanced course with Python. Main purpose is to learn Tkinter

Import Statements: The script imports necessary modules and classes from various files, such as Button and Entry from Tkinter, as well as functions from other modules.

GUI Rendering: The render_entry() function creates two buttons, "Register" and "Login," and places them in the GUI window.

User Data Management: The get_users_data() function reads user information from a file and returns it as a list of dictionaries.

Login Functionality: The login() function clears the screen and creates input fields for username and password. It also places the login button on the screen.

Logging Function: The logging() function checks the entered username and password against the stored user information. If the login credentials are valid, it calls the display_products() function; otherwise, it displays an error message.

Registration Functionality: The register() function clears the screen and creates input fields for first name, last name, username, and password. It also places the registration button on the screen.

Registration Process: The registration() function retrieves the entered information and checks its validity. If the registration is successful, the user information is saved to a file after hashing the password. Then, it calls the display_products() function.

Input Validation: The check_registration() function validates the user input for registration, checking for empty fields and duplicate usernames. It displays error messages if any issues are found.

Event Handling: The print_event() function is bound to the <KeyRelease> event and is used to enable or disable the login button based on whether the username and password fields are empty or not.

Entry Widgets: The script creates Entry widgets for the input fields required for registration and login. These widgets are used to capture user input.

Key Binding: The root.bind("<KeyRelease>", print_event) line binds the <KeyRelease> event to the print_event() function, which allows for event-based handling of key releases.

![image](https://github.com/IvanVakov/GUI-Shop/assets/119103300/fc0a1d3a-3a0b-4f8f-9284-84ad3932ad16)

![image](https://github.com/IvanVakov/GUI-Shop/assets/119103300/49aa3ff5-38b7-4e6a-9b21-3fbac69bcd55)

![image](https://github.com/IvanVakov/GUI-Shop/assets/119103300/903e97ca-1a6e-4d32-9a76-81be1dae8204)




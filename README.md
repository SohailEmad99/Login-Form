# Login Form Task

A Java desktop application demonstrating a login and sign-up workflow using Java AWT.

## Features

- **Login** with username, password, and role selection.
- **Sign up** with required-field validation, unique usernames, password confirmation, and a minimum password length of four characters.
- **Role validation** for Student, TA, and Professor accounts.
- **Failed-login lockout:** after three failed attempts, login and sign-up actions are disabled for 30 seconds with a countdown message.
- **Welcome screen** after a successful login, displaying the username and role.
- **Login and sign-up screens** within one window using `CardLayout`.

## Screenshots

The four screenshots below are embedded from the image files in this repository. Keep the image files in the repository root with these exact names so GitHub can display them.

### Screenshot 1

![Screenshot 1](Screenshot%202026-10-23%20043955.png)

### Screenshot 2

![Screenshot 2](Screenshot%202026-10-23%20044026.png)

### Screenshot 3

![Screenshot 3](Screenshot%202026-10-23%20044103.png)

### Screenshot 4

![Screenshot 4](Screenshot%202026-10-23%20044131.png)

## Built With

- Java
- AWT components and layout managers
- `javax.swing.Timer` for the lockout countdown

## Project Files

- `LoginFormTask.java` — application source code.
- `README.md` — project documentation.
- `Screenshot 2026-10-23 043955.png` — screenshot 1.
- `Screenshot 2026-10-23 044026.png` — screenshot 2.
- `Screenshot 2026-10-23 044103.png` — screenshot 3.
- `Screenshot 2026-10-23 044131.png` — screenshot 4.

## Run the Application

Install a JDK, open a terminal in the folder containing `LoginFormTask.java`, and run:

```bash
javac LoginFormTask.java
java LoginFormTask
```

## Demo Accounts

The application includes these sample accounts:

| Username | Password | Role |
|---|---|---|
| `ahmed` | `1234` | Student |
| `sara` | `abcd` | TA |
| `drmohamed` | `pass123` | Professor |

You can also create an account using the sign-up screen. Accounts are stored in memory and are lost when the application closes.

## Security Note

This is a learning/demo project. Passwords are stored as plain text in memory, so this implementation is **not suitable for production use**.

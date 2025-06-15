# Password Validation

A simple web application to validate and confirm user passwords, ensuring they meet a minimum length requirement and match each other. Features a clean UI with real-time feedback and a custom favicon.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Requirements](#requirements)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project_structure)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Password Validation**: Ensures passwords are at least 5 characters long and not empty.
- **Password Matching**: Verifies that the password and confirmation password are identical.
- **User Feedback**: Displays color-coded messages (red for errors, green for success) that disappear after 3 seconds.
- **User Tip**: Informs users of the 5-character minimum requirement.
- **Favicon**: Custom icon in the browser tab for a polished look.
- **Simple UI**: Clean, centered layout for ease of use.

## Screenshots
| Password Validation Form |
|--------------------------|
| <img src="screenshots/screenshot.png" alt="Password Validation Screenshot" width="300"/> |

## Requirements
- Web browser (e.g., Chrome, Firefox, Edge)
- Git (optional, for cloning the repository)
- Visual Studio Code with Live Server extension (optional, for real-time previews)
- Code editor (e.g., VS Code) for customization (optional)

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/johnkoshy/Password-Validation-Website.git
   cd Password-Validation-Website
   ```
2. Open the webpage:
   - **Option 1: Live Server (Recommended)**:
     - Install the Live Server extension in Visual Studio Code.
     - Right-click `index.html` and select **Open with Live Server** to view at `http://127.0.0.1:5500`.
   - **Option 2: Direct Open**:
     - Open `index.html` in a browser:
       ```bash
       # macOS
       open index.html
       # Linux
       xdg-open index.html
       # Windows
       start index.html
       ```
3. Customize favicon (optional):
   - Replace `favicon.ico` with your own icon (16x16 or 32x32, `.ico` or `.png`).
   - Update the `<link>` tag in `index.html` if needed.

## Usage
1. Open the website in a browser (`http://127.0.0.1:5500` with Live Server or directly via `index.html`).
2. Enter a password and confirmation password in the form.
3. Ensure both are at least 5 characters long and match.
4. View feedback messages (e.g., "Passwords match" in green or "Passwords does not match" in red).
5. Note the custom favicon in the browser tab.

## Project Structure
- **index.html**: Main HTML file with form, JavaScript, and inline styles.
- **favicon.ico**: Custom favicon for the browser tab.
- **screenshots/**: Stores app screenshots.

## Technologies
- **HTML5**: Markup for the form structure.
- **CSS3**: Inline styles for the UI layout.
- **JavaScript**: Client-side validation and feedback logic.

## Contributing
Contributions are welcome! 🎉 Created by John Koshy. For issues, suggestions, or improvements, please open an issue or submit a pull request on [GitHub](https://github.com/johnkoshy/Password-Validation-Website/issues).

## License
This project is licensed under the [MIT License](LICENSE).
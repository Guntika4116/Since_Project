# Since Project Registration Form

This project is a web-based registration form for a business development support (BDS) program. It allows users to submit their personal and business information through a structured form.

## Project Structure

```
Since_Project
├── index.html          # HTML structure for the registration form
├── src
│   ├── css
│   │   └── styles.css  # Custom CSS styles for the project
│   └── js
│       └── main.js     # JavaScript code for form functionality
├── .gitignore          # Files and directories to be ignored by Git
├── package.json        # npm configuration file
└── README.md           # Documentation for the project
```

## Features

- **Responsive Design**: The form is styled using Bootstrap to ensure it looks good on all devices.
- **Form Validation**: JavaScript functions validate user input to ensure data integrity.
- **Dynamic Input Fields**: Certain fields appear based on user selections (e.g., SME One ID).
- **Success Message**: After successful registration, a confirmation message with a large checkmark is displayed.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd Since_Project
   ```

2. **Install Dependencies**:
   If you are using npm, run:
   ```bash
   npm install
   ```

3. **Open the HTML File**:
   Open `index.html` in your web browser to view and interact with the registration form.

## Usage

- Fill in the required fields in the registration form.
- Upon submission, if the registration is successful, a confirmation message will be displayed.
- The form can only be submitted once; subsequent visits will show the success message.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
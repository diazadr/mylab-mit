# MyLAB Application

![Project Status](https://img.shields.io/badge/status-completed-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue)

This project is developed as part of the Cloud Computing 2 course. It showcases an application for managing lab attendance and inventory, utilizing Firebase for cloud-based authentication and Google Spreadsheet for cloud storage.

## Technologies Used
- **MIT App Inventor**: Development platform for the application.
- **Firebase**: User authentication and account management.
- **Google Spreadsheet**: Data storage for attendance and inventory.
- **Web Component**: Integration with third-party services.

## Features
- **Firebase-based Login**: Secure user authentication.
- **Google Spreadsheet Integration**: Real-time data storage for attendance and inventory.
- **Attendance Management**: Track lab attendance with options for absence or lab entry.
- **Inventory Management**: Manage and document lab inventory items.
- **User-Friendly Interface**: Easy navigation with splash screen, login, and menu pages.

## Demo
### Splash Screen
- Displays for 3 seconds before transitioning to the Login Page.
  
  <img src="https://github.com/user-attachments/assets/5efaa79b-d1fe-47c3-887c-6b127b252266" alt="Splash Screen" title="Splash Screen" style="height: 300px; width: auto;">

### Login Page
- Firebase authentication for registered users.
- Registration option for new users.
- Error notifications for invalid login attempts.

  <img src="https://github.com/user-attachments/assets/4ec4cf47-f120-43aa-bb7a-8a397a6a7eaf" alt="Login Page" title="Login Page" style="height: 300px; width: auto;">

### Attendance Screen
- Spinner for attendance options.
- Save & Exit for absent users.
- Save & Enter Lab for users performing inventory tasks.

  <img src="https://github.com/user-attachments/assets/f429baa0-2ba8-4d0f-86d9-dc90d64477f2" alt="Attendance Screen" title="Attendance Screen" style="height: 300px; width: auto;">

### Lab Inventory Menu
- List of labs with images for selection.

  <img src="https://github.com/user-attachments/assets/9e2bccb3-b822-49ae-a558-500d8a8a5d22" alt="Lab Inventory Menu" title="Lab Inventory Menu" style="height: 300px; width: auto;">

### Lab Inventory Page
- Enter item descriptions to check lab inventory.
- Data sent to Google Spreadsheet for documentation.

  <img src="https://github.com/user-attachments/assets/58a2f3c1-a19e-47b8-bf19-bc096b5f1cc8" alt="Lab Inventory Page" title="Lab Inventory Page" style="height: 300px; width: auto;">

### Google Spreadsheet Integration
- Google Form linked to Spreadsheet for data storage.
- Prefilled link used to connect the app with Google services.

  <img src="https://github.com/user-attachments/assets/442707c0-f582-4855-93f5-f3d924620c4d" alt="Google Spreadsheet Integration" title="Google Spreadsheet Integration" style="height: 300px; width: auto;">

## Setup
1. **Firebase Configuration**: Set up Firebase for authentication and link it to the app.
2. **Google Spreadsheet**: Create a Google Form linked to a Spreadsheet and configure it to match app input fields.
3. **Prefilled Link**: Obtain the prefilled link from the Google Form and integrate it into the app.

## Usage
1. Launch the app.
2. Log in using Firebase credentials or register as a new user.
3. Use the attendance screen to mark presence or absence.
4. Select a lab from the inventory menu to manage items.
5. Enter item details in the inventory page, which are automatically saved to the Google Spreadsheet.

## Project Status
This project is **completed** and will not be further developed.

## Acknowledgements
- **MIT App Inventor Community**: For providing the development platform.
- **Firebase & Google Services**: For enabling secure authentication and data storage.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

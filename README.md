# MyLAB Application

This application is designed to assist in managing lab attendance and inventory processes. It includes features such as Firebase-based login, Google Spreadsheet integration, and inventory data management.

---

## **DEMO**

### **Splash Screen**
- A splash screen is displayed when the application is launched, with a `TimerInterval` of 3000 milliseconds (3 seconds). 
- After the timer expires, the app automatically transitions to the **Login Page**.
<img src="https://github.com/user-attachments/assets/5efaa79b-d1fe-47c3-887c-6b127b252266" alt="Splash Screen" style="height: 300px; width: auto;">

---

### **Login Page**
- Users can log in using accounts registered via the application.
- **FirebaseDB** is used for account authentication, with user data stored in the Firebase database.
- Users without an account can register via the **Register** button by filling in the required fields in the `TextBox`.
- Notifications for invalid usernames or login errors are displayed using the `Notifier` component.
<img src="https://github.com/user-attachments/assets/4ec4cf47-f120-43aa-bb7a-8a397a6a7eaf" alt="Login Page" style="height: 300px; width: auto;">

---

### **Attendance Screen**
- After logging in, users are directed to the attendance page.
- **Spinner Component**: Allows users to select attendance options.
- **Google Spreadsheet Integration**: Attendance data is stored in a Google Spreadsheet via the `Web` component.
- **Buttons**:
  - **Save & Exit**: For users who are absent (sick or on leave), the attendance record is marked with a `"-"` symbol.
  - **Save & Enter Lab**: For users who will perform lab inventory tasks, they are redirected to the **Lab Inventory Menu**.
<img src="https://github.com/user-attachments/assets/f429baa0-2ba8-4d0f-86d9-dc90d64477f2" alt="Attendance Screen" style="height: 300px; width: auto;">

---

### **Lab Inventory Menu**
- This page displays a list of available labs with corresponding images.
- Users can select their target lab for inventory management.
<img src="https://github.com/user-attachments/assets/9e2bccb3-b822-49ae-a558-500d8a8a5d22" alt="Lab Inventory Menu" style="height: 300px; width: auto;">

---

### **Lab Inventory Page**
- On this page, users can check the items available in the lab by entering item descriptions.
- Inventory data is sent to a specific lab spreadsheet using the `Web` component for documentation and tracking.
<img src="https://github.com/user-attachments/assets/58a2f3c1-a19e-47b8-bf19-bc096b5f1cc8" alt="Lab Inventory Page" style="height: 300px; width: auto;">

---

### **Google Spreadsheet Integration**
- The application uses Google Spreadsheet as a third-party service to store attendance and inventory data.
- **Setup Instructions**:
  1. Create a **Google Form** linked to a Google Spreadsheet.
  2. Add questions and answers in the Google Form to match the input fields in MIT App Inventor.
  3. Obtain the prefilled link from the Google Form and paste it into the application.
  4. Data entered in the app is automatically recorded in the Google Spreadsheet.
<img src="https://github.com/user-attachments/assets/442707c0-f582-4855-93f5-f3d924620c4d" alt="Google Spreadsheet Integration" style="height: 300px; width: auto;">

---

## **Technologies Used**
- **MIT App Inventor**: The development platform for the application.
- **Firebase**: Used for user authentication and account management.
- **Google Spreadsheet**: Serves as the data storage for attendance and inventory.
- **Web Component**: Connects the application to third-party services.

---

## **How to Use**
1. Set up Firebase for authentication and link it to the application.
2. Configure Google Form and Spreadsheet for data storage.
3. Use the provided prefilled link to connect the app with Google services.
4. Launch the app and follow the workflow to manage attendance and inventory effectively.

---

## **Contributions**
Feel free to submit issues or contribute to this project by creating pull requests.

---

Thank you for using the MyLab Application!

Employee Management Mobile Application
Overview
This mobile application is designed for a company to manage employee data effectively, with distinct admin and employee functionalities. Admins can add, edit, and manage employee details, including leave approvals, while employees can view and edit their details, manage leave requests, and adjust notification preferences.

This project currently implements the employee-side user interface in Android Studio using Java, focusing on a high-fidelity prototype without functional Java components.

Features
Employee Side Functionalities
Login Screen

Allows employees to log in securely.
Provides a clear "Forgotten your password?" option for easy password recovery.
Employee Dashboard

Displays key information and navigational options.
Acts as the main hub, allowing access to other employee features.
Request Leave Screen

Employees can select leave dates and submit leave requests.
Shows the remaining leave balance for transparency.
Notifications Screen

Displays notifications related to leave requests and company updates.
Provides a settings option for managing notification preferences.
Notification Settings Screen

Enables employees to toggle notifications for:
Holiday requests
Personnel updates
Sound
Vibration
Includes a "Save Changes" button to store settings.



Key Components
LoginActivity.java: Manages the login screen layout and UI components.
DashboardActivity.java: Contains the main dashboard with navigation options.
RequestLeaveActivity.java: Manages leave request input and displays leave balance.
NotificationsActivity.java: Displays user notifications and includes a button to access notification settings.
NotificationSettingsActivity.java: Contains toggles for managing notification preferences and a save button.

Resources
layout/: XML files for each activity's layout, implementing the UI elements and layouts.
values/: Resource files for strings, colors, and styles to maintain consistency across the app.


Installation and Setup
Clone the Repository
Open in Android Studio
Launch Android Studio and select Open an existing project.
Navigate to the cloned repository and open the EmployeeManagementApp folder.
Run the Project
Connect an Android emulator or physical device.
Click on Run > Run 'app' to launch the application.

Test Save 2
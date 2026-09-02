# TripVault — Personal Travel Journal

TripVault is a simple and professional **personal travel journal web application** that allows users to create, manage, and store their travel memories.

This version is implemented as a **single HTML file**, making it easy to run without installing Node.js, MongoDB, or any other backend software.

## Features

* User registration
* User login and logout
* Personal dashboard
* Add new trips
* Edit existing trips
* Delete trips
* Trip title and destination
* Start and end dates
* Trip rating from 1 to 5
* Travel notes
* Trip count
* Form validation
* Date validation
* Delete confirmation
* Responsive design
* Professional and attractive interface
* Data persistence using browser `localStorage`

## Technologies Used

* **HTML5** — Application structure
* **CSS3** — Styling and responsive design
* **JavaScript** — Application logic and user interactions
* **LocalStorage** — Saving users and trip information in the browser

## Project Structure

```text
TripVault/
└── index.html
```

The entire application is contained in one file.

## How to Run

### Method 1 — Directly in Browser

1. Download `index.html`.
2. Open the file by double-clicking it.
3. The TripVault application will open in your web browser.
4. Create a new account.
5. Log in using your account.
6. Start adding your trips.

### Method 2 — Using VS Code

1. Open the project folder in Visual Studio Code.
2. Open `index.html`.
3. Install the **Live Server** extension if required.
4. Right-click `index.html`.
5. Select **Open with Live Server**.
6. TripVault will open in your browser.

## How the Application Works

### 1. Registration

A new user can create an account by providing:

* Full name
* Email address
* Password

The account information is stored in the browser's local storage.

### 2. Login

The user enters their registered email and password.

If the credentials are correct, the TripVault dashboard is displayed.

### 3. Dashboard

The dashboard displays all trips belonging to the currently logged-in user.

Each trip displays:

* Trip title
* Destination
* Start date
* End date
* Rating
* Notes

### 4. Add Trip

The user can click **Add Trip** and enter the trip details.

Required fields include:

* Trip title
* Destination
* Start date
* End date
* Rating

The application also checks that the end date is not earlier than the start date.

### 5. Edit Trip

The **Edit** button allows the user to modify an existing trip.

After saving, the updated information immediately appears on the dashboard.

### 6. Delete Trip

The **Delete** button removes a trip from the dashboard.

A confirmation message is displayed before the trip is deleted.

### 7. Data Storage

TripVault uses the browser's **LocalStorage** to save:

* Registered users
* Trip information
* Current login session

Therefore, the information remains available when the browser page is refreshed.

## Validation

The application performs basic validation for:

* Required fields
* Valid email format
* Minimum password length
* Duplicate email registration
* Correct start and end dates
* Rating between 1 and 5

## Responsive Design

TripVault is designed to work on:

* Desktop
* Laptop
* Tablet
* Mobile devices

The dashboard automatically adjusts the trip cards according to the screen size.

## Advantages

* Easy to run
* No backend installation required
* No database configuration required
* Simple project structure
* Fast and lightweight
* Responsive user interface
* Data is retained using LocalStorage
* Suitable for demonstrations and academic projects

## Limitations

This single-page version is a browser-based application and therefore has some limitations:

* Data is stored only in the user's browser.
* Data is not synchronized between different devices.
* There is no cloud database.
* There is no real server-side authentication.
* Clearing browser storage will remove the stored application data.
* Passwords are stored locally and should not be considered secure for a production application.

## Future Enhancements

The project can be extended with:

* MongoDB database
* Node.js and Express backend
* JWT authentication
* Cloud image storage
* Trip photographs
* Google Maps integration
* Search and filtering
* Trip categories
* Weather information
* Travel expense tracking
* Cloud synchronization
* Secure password hashing
* User profile management

## Conclusion

TripVault provides a simple and user-friendly way to maintain a personal digital travel journal. The single-page implementation combines HTML, CSS, and JavaScript into one easily deployable file while providing essential trip management functionality.

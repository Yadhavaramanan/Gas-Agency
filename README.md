# Gas-Agency

This project is a simple web-based management system for gas agencies using Firebase as the backend database. The system allows users to manage client information, including their transactions, balances, and other details. It supports adding new clients, searching, and viewing client data.

## Features

- **Add new client**: Add client data including name, transaction details, amount, and balance.
- **Search functionality**: Filter clients by client name, transaction type, and other details.
- **Firebase Firestore**: All client data is stored and managed in Firebase Firestore.

## Technologies Used

- HTML, CSS, JavaScript
- Firebase Firestore
- Bootstrap (for styling)

## Setup

To run this project locally, follow these steps:

### Prerequisites

- A Firebase account. If you don't have one, you can [sign up here](https://firebase.google.com/).
- Basic knowledge of how to use Firebase Firestore.

### Steps to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/gas-agencies-management.git

   ```

2. Navigate into the project folder:

   ```bash
   cd gas-agencies-management

   ```

3. Open "index.html" in your web browser. You can do this by right-clicking the file and selecting Open with -> Your Browser.

4. Firebase Setup
   - Go to Firebase Console.
   - Create a new project (or use an existing project).
   - Enable Firestore in the Firebase console.
   - Copy the Firebase config object from the Firebase project settings, and replace the firebaseConfig object in script.js with your own Firebase config object.

- Make sure to install the Firebase SDK in your project by running the following command in your terminal
    ```bash
    const firebaseConfig = {
        apiKey: "YOUR_API_KEY",
        authDomain: "YOUR_AUTH_DOMAIN",
        projectId: "YOUR_PROJECT_ID",
        storageBucket: "YOUR_STORAGE_BUCKET",
        messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
        appId: "YOUR_APP_ID"

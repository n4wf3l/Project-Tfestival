# Evenement t'Festival

This project was developed as part of the Trends II course. The objective was to create a functional website for the t'Festival event.

## Table of Contents
- [General Information](#general-information)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)

## General Information
The project involves creating a website for the t'Festival event. The goal was to upgrade the existing website by enabling online payments and integrating a QR code into PDF tickets for entry control. Additionally, it was essential to develop a robust database to store all relevant data.

## Technologies Used
- Firebase
- htmlToPDF API

## Setup
To set up the project locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/tfestival.git
    cd tfestival
    ```

2. **Install dependencies:**
    Ensure you have Node.js and npm installed. Then run:
    ```sh
    npm install
    ```

3. **Setup Firebase:**
    - Create a Firebase project in the Firebase console.
    - Set up Firestore and Firebase Authentication.
    - Add your Firebase project's configuration to a `.env` file.

4. **Environment Variables:**
    Create a `.env` file in the root directory and add your Firebase configuration:
    ```env
    FIREBASE_API_KEY=your_api_key
    FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
    FIREBASE_PROJECT_ID=your_project_id
    FIREBASE_STORAGE_BUCKET=your_project_id.appspot.com
    FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
    FIREBASE_APP_ID=your_app_id
    ```

5. **Run the application:**
    ```sh
    npm start
    ```

## Usage
To use the website, follow these steps:

1. **User Registration and Login:**
    Users can register and log in to the website to purchase tickets.

2. **Purchasing Tickets:**
    Select the desired event and number of tickets. Proceed to checkout and complete the payment process.

3. **Ticket Generation:**
    After purchasing, a PDF ticket with a QR code will be generated and sent to the user’s email.

4. **Admin Controls:**
    Administrators can manage events, view sales reports, and control ticket validations using the admin dashboard.

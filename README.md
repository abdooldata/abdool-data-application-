# Abdool Data Application

## Overview
abdool-data-application- is a versatile data management tool built using HTML, JavaScript, and Paystack for payment integration. The application provides features like Airtime Purchase, Data Purchase, Cable TV Subscription, Electricity Payment, and Complaint Filing. It integrates SMS verification via Twilio and allows seamless payments.

## Features
- **Sign Up & Login:** Users can sign up and log in with their phone numbers.
- **SMS Verification:** Users receive an SMS verification code to authenticate their phone numbers.
- **Paystack Integration:** Allows users to make payments for services using Paystack.
- **Dashboard:** After successful login, users can access a variety of services such as Airtime, Data, Cable, and Electricity bill payments.
- **Complaint Filing & History:** Users can file complaints and view their service history.

## Technologies Used
- **Frontend:** HTML, TailwindCSS, JavaScript
- **Backend:** Node.js (optional if implementing backend services like verification)
- **Payment Gateway:** Paystack
- **SMS Verification:** Twilio

## Setup and Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/abdool-data-application.git
   cd abdool-data-application

2. Setup Twilio

Create a Twilio account at Twilio.

Get your Twilio Account SID, Auth Token, and Verify Service SID.

Update the JavaScript code to include your Twilio credentials.



3. Paystack Integration

Create a Paystack account at Paystack.

Use the Paystack public key in your application for handling payments.

Update the Paystack public key in the script provided in the HTML file.



4. Running the Application

Since this is a frontend application, no backend is needed for running the HTML file.

Open the index.html file in a browser to interact with the application.




Folder Structure

abdool-data-application/
│
├── index.html          # Main HTML file with the app's structure and logic
└── README.md           # Project README file

Contributions

Feel free to fork the repository and contribute by making pull requests.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact

For support or inquiries, contact us at: auh439@gmail.com.

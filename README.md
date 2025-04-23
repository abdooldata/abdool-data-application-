# Abdool Data Application

Abdool Data Application is a data management web application designed to provide users with various features such as:

- **Sign Up / Login**
- **Dashboard** for managing data
- **SMS Verification** via Twilio for user authentication
- **Paystack Integration** for payments (Airtime, Data, Cable, Electricity)
- **File Complaints** and view user history
- **Full User Interaction** with various functionalities like buying airtime, data, and paying bills.

## Features

- **User Authentication:** Users must register and log in before accessing the dashboard.
- **SMS Verification:** Users are verified via SMS using Twilio's SMS service.
- **Paystack Payment Integration:** Seamlessly buy airtime, data, cable TV subscriptions, and pay electricity bills.
- **Complaints & History:** Users can file complaints and view their transaction history.
- **Responsive Design:** Fully responsive and mobile-friendly UI built using Tailwind CSS.

## Tech Stack

- **Frontend:** HTML, Tailwind CSS, JavaScript
- **Backend:** Node.js (for SMS verification and other back-end services)
- **Payment Integration:** Paystack (for payments)
- **SMS Verification:** Twilio (Twilio Verify API)

## Installation

### Prerequisites

- Node.js and npm installed on your machine.
- Twilio account with access to the Verify API.
- Paystack account for live payment integration.

### Steps to Install:

1. Clone the repository:

   ```bash
   git clone https://github.com/abdooldata-app/abdool-data-application.git
   cd abdool-data-application

2. Install dependencies (for backend setup):

npm install


3. Create a .env file and add your Twilio and Paystack keys:

TWILIO_ACCOUNT_SID=your_account_sid
TWILIO_AUTH_TOKEN=your_auth_token
TWILIO_VERIFY_SID=your_verify_sid
PAYSTACK_PUBLIC_KEY=your_paystack_public_key


4. Start the app:

npm start


5. Open your browser and visit http://localhost:3000.



Twilio Setup

To integrate Twilio for SMS verification, you need to create a Twilio account and get your Twilio credentials. Follow these steps:

1. Create a Twilio Account: Visit Twilio and sign up for an account.


2. Get Account SID and Auth Token: Once you sign up, you will get your Account SID and Auth Token from the Twilio Console.


3. Get the Verify SID: You can create a Verify Service in the Twilio Console to get the Verify SID for sending SMS verification codes.


4. Set Environment Variables: Add your Twilio credentials to the .env file as shown below:

TWILIO_ACCOUNT_SID=your_account_sid
TWILIO_AUTH_TOKEN=your_auth_token
TWILIO_VERIFY_SID=your_verify_sid



Paystack Setup

To integrate Paystack for payments, you will need your Paystack public key. You can get this from the Paystack dashboard.

1. Get Paystack Public Key: Log in to your Paystack account and navigate to the "API Keys & Webhooks" section.


2. Set Environment Variables: Add your Paystack public key to the .env file as shown below:

PAYSTACK_PUBLIC_KEY=your_paystack_public_key



Usage

Sign Up: Enter your phone number to create a new account.

Login: Use your registered phone number to log in.

Dashboard: Access all features after logging in, including purchasing airtime, data, and making payments.

SMS Verification: A verification code will be sent to your phone for both signup and login.


Contribution

Feel free to fork the project, make improvements, and submit pull requests. If you encounter any issues or have feature requests, please open an issue in the GitHub repository.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact

For any questions, please contact us at auh439@gmail.com.

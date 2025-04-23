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
- **SMS Verification:** Twilio

## Installation

### Prerequisites

- Node.js and npm installed on your machine.
- Twilio account with access to the Verify API.
- Paystack account for live payment integration.

### Steps to Install:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/abdool-data-application.git
   cd abdool-data-application

2. Install dependencies (for backend setup):

npm install


3. Create a .env file and add your Twilio and Paystack keys:

TWILIO_ACCOUNT_SID=AC8a2ca4235af75173d6a804a33c4656df
TWILIO_AUTH_TOKEN=33c0e1c16cacbbe4ea988068990b5992
TWILIO_VERIFY_SID=VA33be0e09cf12d212245485efaf33395c
PAYSTACK_PUBLIC_KEY=pk_live_fefa4cab21e99bd551e0979a445038b389d9cfea


4. Start the app:

npm start


5. Open your browser and visit http://localhost:3000.



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

For any questions, please contact us at auh439@gmail.com

Patient Management System :~

* This Patient Management System is a full-stack application designed to facilitate management of patient records, appointments, prescriptions, and communication between doctors and patients. The system is built with a React frontend and a Node.js/Express backend, using MongoDB for data storage.

Features :~

->User Authentication: Secure login and registration with JWT.
-> Role-Based Access Control: Separate roles for doctors, patients, and admins.
-> Appointment Management: Schedule, view, and categorize appointments by 'Today,' 'Upcoming,' 'Previous,' and 'Canceled'.
-> Patient Records: Doctors can create and view patient records.
-> Prescription Management: Doctors can create and manage prescriptions, which patients can view.
-> Chat and Video Consultation: Real-time chat and video call functionality for consultations.
-> Image Upload: Profile and signature image uploads for users.
-> Notifications: Appointment and task-related notifications for users.
-> Secure Payment Processing: Integrated PayPal for secure payments.

Tech Stack :~

-> Frontend: React, Tailwind CSS
-> Backend: Node.js, Express.js
-> Database: MongoDB
-> Real-Time Communication: Socket.io
-> File Upload: Multer
-> Authentication: JSON Web Token (JWT)

Installation :~

Prerequisites :~

-> Node.js and npm
-> MongoDB
-> A .env file with the following variables:

PORT=8000
DB_URL=<your-mongodb-connection-string>
JWT_SECRET=<your-jwt-secret>
EMAIL_USER=<your-email-address>
EMAIL_PASSWORD=<your-email-password>

Steps :~

1. Clone the Repository :~

=> git clone https://github.com/HeetMorker/Team-Horizon--PMS--.git
=> cd Team-Horizon--PMS--

2. Backend Setup :~

* Navigate to the backend folder :~
=> cd backend

* Install backend dependencies :~
=> npm install

* Start the backend server :~
=> npm run dev

3. Frontend Setup :~

* Navigate to the backend folder :~
=> cd ../frontend

* Install Frontend dependencies :~
=> npm install

* Start the backend server :~
=> npm start


The frontend should be available at http://localhost:3000 and the backend at https://team-horizon.onrender.com.


* Project Structure :~

* Backend :~

=> src/config: Configuration files for database and server settings.
=> src/controllers: Logic for handling API requests.
=> src/routes: API routes for user, appointment, prescription, and chat features.
=> src/utils: Utility functions for sockets, file uploads, and other helpers.

* Frontend :~
=> src/components: Reusable UI components for forms, buttons, modals, etc.
=> src/pages: Main pages such as Dashboard, Appointments, Patient Records, and Profile.
=> src/services: API calls and data-fetching logic.

* API Endpoints :~

=> User: Registration, Login, Profile management
=> Appointments: Create, View, Edit, Delete, and Categorize
=> Patient Records: Add, View, and Edit patient records
=> Prescriptions: Create and View prescriptions
=> Chat: Real-time chat and video consultation setup
=> Payments: Payment integration for consultations

* Troubleshooting :~
=> If you encounter issues with ports or the application not starting, verify that:

1. The ports (default 8000 for backend and 3000 for frontend) are not in use by another process.
2. Your .env file is correctly set up with all required environment variables.

* Acknowledgments :~
=> Special thanks to Dhruvisha for her contribution in this project.
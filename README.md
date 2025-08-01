#  Healthcare  Appointment Booking Using MERN

### 🚀 [🌐 Project Demo](https://drive.google.com/file/d/14QlsjXGk4wvU7D_0lv3FPq-MyTA-9Irk/view?usp=drive_link)

---

## 🩺 Overview
A full-stack web application built with the MERN stack that allows patients to book appointments with doctors. 
Admins and doctors can manage their schedules, appointments, and patient records. 
Users can register, log in, search for doctors, and book appointments online.

---

##🚀 Tech Stack / Tools & Libraries Used
1)🔧 Frontend (React.js)
   **React.js – UI development
   **React Router – Routing between pages
   **Axios – For HTTP requests
   **Tailwind CSS – Styling
   **Toastify – Notifications & alerts

2)🖥️ Backend (Node.js + Express.js)
  -Express.js – Server-side routing & API logic
  -Node.js – Backend environment
  -Mongoose – MongoDB object modeling

3)🛢️ Database
   -MongoDB Atlas – Cloud database to store user and appointment data

4)🔒 Authentication
  -JWT (JSON Web Tokens) – Secure user login & session handling
  -bcryptjs – Password hashing

---
##✨ Features
-User Registration/Login
-Role-based access (Patient / Doctor / Admin)
-Book / Cancel Appointments
-View Available Slots
-Doctor Profile Management
-Admin Dashboard (Manage Doctors, Users, Appointments)
-Responsive design for mobile and desktop

---
## 🧗 Challenges Faced & Solutions
1. Role-Based Access Control
Challenge: Differentiating views and permissions between Admins, Doctors, and Patients.
Solution: Implemented JWT tokens with role attributes; protected routes on frontend and backend.

2. Appointment Conflicts
Challenge: Avoiding overlapping bookings for the same time slot.
Solution: Added backend validation to check for existing appointments before confirming.

3. Time Slot Management
Challenge: Dynamically generating available slots based on doctor schedule.
Solution: Created a helper logic to generate slots for each doctor and track booked/unavailable times.

4. Form Validation
Challenge: Ensuring accurate input from users during registration or appointment booking.
Solution: Used Formik and Yup for frontend validation and added backend schema validation.

5. State Management
Challenge: Managing shared state like user info and appointment data across components.
Solution: Used React Context API and localStorage for persistence across sessions.





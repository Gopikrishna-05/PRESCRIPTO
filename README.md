# Doctor Appointment Booking System (MERN Stack)  

## Description  

This full stack appointment booking system can be used by a doctor or a hospital. Because in this project I have created 3 level of authentication. 1st one is for Patients, so that patient can login on the website, book appointment with doctor and manage the booked appointment. 2nd one is doctor login, so that doctor can login and check the appointment and their earning. Doctor can update their profile also from dashboard. 3rd one is Admin Dashboard where admin can manages the appointment and admin can also manage the doctor profile.  

## Features  

- **Frontend**:Built with Vite React, including pages for Home, Doctor List, Appointment Booking, Patient Dashboard, Doctor Dashboard, Admin Panel, Login/Signup

- **Backend**:Node.js and Express handle APIs, user authentication, appointment scheduling, and database operations.  

## Authentication (3 Levels)
- **Patient Authentication**: Register, login, and manage appointments

- **Doctor Authentication**: Login, view appointments, update profile, check earnings

- **Admin Authentication**: Full access to manage doctors, appointments, and system data  

## Appointment Management
- Patients can book, reschedule, or cancel appointments

- Doctors can approve or reject appointments

- Admin can monitor all appointments and activity   

## Admin Dashboard:

- Displays appointment statistics

- Manages doctors and users

- Tracks payments and revenue

- **Payment Integration**:Supports Razorpay for secure transactions.  

- **Image Uploads**:Uses Cloudinary and Multer for efficient image storage and handling.  

- **Deployment**:Fully deployed on Vercel for easy access.  

## Project Structure  

1. **Frontend**: React-based UI with role-based routing
2. **Backend**:API development with Express and MongoDB
3. **Authentication**:JWT-based secure login for Patients, Doctors and Admin
4. **Appointment Management**:Booking, cancellation, approval and history
5. **Payments**:Secure integration with Stripe and Razorpay
6. **Admin Dashboard**:Manage doctors, patients, and appointments
7. **Image Uploads**:Implemented using Cloudinary and Multer
8. **Deployment**:Final hosting on Vercel

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Gopikrishna-05/PRESCRIPTO.git

2.  **Navigate to the project directory**   
    ```bash  
    
     cd PRESCRIPTO  

3. **Install dependencies for frontend, backend and admin**  
    ```bash
   cd frontend  

   npm install  
  
   cd ../backend  

   npm install  

   cd ../admin  

   npm install  

4. **Start three development servers separately**

    ```bash
    
   cd frontend  

   npm run dev  
 
   cd backend  

   node server.js  
  
   cd admin  

   npm run dev  

5. Open http://localhost:5174/ in your browser  

## Technologies Used  

**Frontend** : React,React Router       
**Backend** : Node.js, Express, MongoDB        
**Authentication** : JWT                              
**Payment** : Razorpay                 
**Image Uploads** : Cloudinary, Multer               
**Deployment** : Vercel  

## Deployment  

To deploy the project on Vercel:  

1.Push the code to GitHub.  

2.Connect the repository to Vercel.  

3.Deploy both the frontend and backend separately.  

## Contributors  

Gopi Krishna - [Github Profile](https://github.com/Gopikrishna-05/PRESCRIPTO)  

## License  

This project is licensed under the MIT License.
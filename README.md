🏨 Hostelgia: Hotel Management System
## Description
Hostelgia is a robust and feature-rich Hotel Management System designed to simplify and streamline hostel and hotel management. Built with modern web technologies, this application enables users to manage bookings, track occupancy, handle payments, and ensure a seamless experience for both staff and guests.


## 🚀 Getting Started
1. Clone the Repository
Start by cloning the repository:
git clone https://github.com/your-username/hostelgia-hotel-management.git  
cd hostelgia-hotel-management  


2. Install Dependencies
Run the following command to install the required dependencies: npm install  

3. Set Up the Database
npx prisma migrate dev  
 

4. Start the Application
Run the development server: npm run dev  
Visit the application at http://localhost:3000.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

DATABASE_URL=your_postgres_database_url  
RAZORPAY_KEY_ID=your_razorpay_key_id  
RAZORPAY_KEY_SECRET=your_razorpay_key_secret  
JWT_SECRET=your_jwt_secret  
CLOUDINARY_URL=your_cloudinary_api_url  




## Features

- User Authentication
Secure login and signup for staff and guests using JWT.
- Room Management
Add, update, and manage room availability and types.
- Booking System
Simple and efficient booking flow.
Guests can check availability and book rooms seamlessly.
- Payment Integration
Razorpay integration for secure payment handling.
- Reporting and Analytics
Generate detailed reports on bookings, occupancy, and revenue.
- Image Management
Upload and manage room and property images using Cloudinary.


## Tech Stack
    
- **Next.js**	Framework for building SSR and static apps.
- **ShadCN UI**	Elegant UI components for modern design.
- **PostgreSQL**	Relational database for data management.
- **Razorpay**	Payment gateway for subscriptions.
- **Kinde**	User authentication and session management.
- **Express.js**	Web application framework for APIs.

## Acknowledgements

- React.js and Express.js for a seamless full-stack development experience.
- PostgreSQL for reliable and scalable database management.
- Razorpay for secure and efficient payment handling.
- Cloudinary for simplifying image management.
All contributors for their valuable efforts!


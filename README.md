# StyleDecor – Decoration Service Appointment System

**StyleDecor** is a modern, full-stack appointment management web application built for a local decoration company. It allows customers to browse decoration packages, book in-studio consultations or on-site services, check decorator availability, make secure payments, and track project status in real-time. The system also provides powerful admin tools for managing decorators, assignments, payments, and business analytics.

### Purpose
Local decoration businesses often struggle with walk-in crowds, long waiting times, manual scheduling, and poor coordination for on-site services. **StyleDecor** solves these problems by offering:

- Online booking & smart slot management  
- Real-time decorator availability & specialty tracking  
- On-site service assignment workflow  
- Integrated payment processing  
- Project status updates for customers  
- Admin dashboard with analytics and insights  

This results in a smoother experience for customers and more efficient operations for the business.

### Live URL
Frontend Live URL: https://style-decor-auth.web.app/
Bckend URL: https://style-decor-server-bice.vercel.app/


### Key Features
- **Browse Services & Packages** – View detailed decoration services with images, descriptions, and pricing  
- **Smart Appointment Booking** – Select date, time, service mode (studio / on-site), and preferred decorator  
- **Decorator Management** – Admin can add/edit decorators, set availability, and assign specialties  
- **Payment Integration** – Secure online payment for packages and services  
- **On-site Service Workflow** – Admin assigns decorator teams; decorators update project progress  
- **Real-time Status Tracking** – Customers see booking → payment → assignment → in-progress → completed  
- **Responsive Design** – Fully mobile-friendly UI with Tailwind CSS  
- **Admin Dashboard** – Analytics, booking overview, revenue charts, and user management  
- **Authentication** – Firebase-based email/password and social login  
- **Interactive Elements** – Carousel, animations (Framer Motion), maps (Leaflet), and modals  

### Technology Stack
- **Frontend**: React, Tailwind CSS  
- **State Management**: TanStack React Query  
- **Backend/API**: Express/Node server 
- **Authentication**: Firebase Authentication  
- **Payments**: Integrated payment gateway (Stripe)  
- **Charts & Visualizations**: Recharts  
- **UI Enhancements**: Swiper, Framer Motion (animations), SweetAlert2 (alerts), React Icons  

### NPM Packages Used
```json
"cors": "^2.8.5",
"dotenv": "^17.2.3",
"express": "^5.2.1",
"firebase-admin": "^13.6.0",
"mongodb": "^7.0.0",
"stripe": "^20.0.0"

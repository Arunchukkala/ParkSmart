# ParkSmart
A full-stack web application similar to ParkMobile that allows users to locate, view, and book nearby parking spots in real time. The system helps users find available spaces in multiple regions, while administrators manage parking lots, pricing, and availability through a secure dashboard.

The app includes separate User and Admin roles, secure login/registration, booking management, and real-time spot updates.


Key Functionalities & Features:
🔹 1. User Authentication & Login System

Secure login & registration for Users and Admins

Role-based access (User dashboard vs Admin dashboard)

JWT authentication or Spring Security

🔹 2. Real-Time Parking Spot Availability

Spots marked as Available, Occupied, Reserved

Auto-refresh availability every few seconds

Color-coded UI indicators

🔹 3. Nearby Parking Spot Detection

Uses geolocation (GPS)

Sort spots by distance

Display walking distance/time to destination

🔹 4. Region-Based Parking Listing

Predefined regions (e.g., Downtown, Midtown, TechPark)

Each region contains 10+ parking spots

Availability summary per region

🔹 5. Advanced Filtering & Sorting

Users can filter by:

Distance

Price

Covered/Uncovered

EV charging

Handicap accessible

🔹 6. Parking Spot Booking System

Users can:

Select spot → Start session

End session

View cost summary

Admins can:

Override bookings

Block spots for maintenance

🔹 7. Vehicle Management

Add multiple vehicles

Select vehicle during booking

Store license plate, type (car/bike/EV)

🔹 8. Payment Integration

Stripe, PayPal, Google Pay (optional)

Generate invoices

View transaction history

🔹 9. Admin Management System

Admin can:

Manage regions/lots/spots (CRUD)

Adjust pricing and rules

View all user bookings

Manage user accounts

Control availability manually

🔹 10. Analytics Dashboard (Admin)

Includes:

Total spots

Currently occupied/available

Daily/weekly revenue

Peak usage hours

Heatmap of busy regions

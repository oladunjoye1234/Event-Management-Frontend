Overview:
This is a full-stack web application designed to streamline event management, allowing users to create, browse, book, and manage events.
 The platform supports two user roles: Organizers and Attendees. Organizers can post and manage events, while attendees can browse and book events.
Key Features:
User Authentication:

Signup/Login for both Attendees and Organizers

Role-based rendering and access control

Auth context with persistent session management

Event Management:

Organizers can create, edit, and delete events

Attendees can view and book events

Attendees can cancel bookings

Dashboard:

Personalized dashboard for each role

Profile view and update capability

Booked or created events listing

Email Notifications:

Users receive confirmation emails upon account creation and event booking

Emails are sent using Gmail SMTP via Nodemailer

QR Code / Ticket Integration:

(Optional) Send a QR code or ticket as part of booking confirmation (planned/partial)

Responsive UI:

Built with Tailwind CSS for mobile-friendly, modern design

Animated components for smooth UX

🔐 Environment Configuration:
Uses .env files for sensitive data like:

APP_EMAIL, APP_PASSWORD

EMAIL_HOST, EMAIL_PORT

Backend_Url, JWT secrets, etc.
Digital Housing Management with route mapping and chatbot integration.

<!---
kakay22/kakay22 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


Introduction
The Housing Management System (HMS) is a web-based application designed to streamline and manage housing communities. The system offers an intuitive and user-friendly platform for homeowners, secretaries, and administrators to handle essential tasks such as property management, maintenance requests, event organization, notifications, and communication within the community. Built using Django, the application leverages modern web technologies like Bootstrap, Tailwind CSS, JavaScript, some jQuery and Leaflet for interactive mapping with implementation of Augmented reality.

Features
1. User Management
Homeowner Registration and Login: Allows homeowners to register, log in, and access personalized content.
Role-based Access: Different dashboards for homeowners, secretaries, and admins with role-specific functionalities.
Admin Panel: Manage users, properties, and events with full control over the system.

3. Property Management
Property Details: View and manage detailed information about properties, including ownership history, location, and current status.
Maintenance Requests: Homeowners can submit maintenance requests, track the status, and verify completion.

5. Maintenance Request System
Request Submission: Homeowners can describe issues, specify locations, and choose issue types when submitting maintenance requests.
Status Tracking: Track the status of requests (e.g., Pending, In Progress, Done), and receive real-time notifications when status changes.
Completion Verification: Homeowners can verify if the issue has been fixed before closing the request.

6. Event Management
Event Creation: Secretaries and admins can create and manage community events, view RSVPs, and share event details.
Comments on Events: Homeowners can comment on event posts and interact with others, receiving notifications for new comments.

7. Real-time Notifications
Request Status Updates: Homeowners receive notifications when their maintenance requests change status.

Event Notifications: Stay informed of upcoming community events and other announcements.

Bell Icon Indicator: Real-time indicator for new notifications with a smooth and interactive UI.

Route Mapping with Leaflet
Interactive Maps: Provides homeowners with a map view of the community, properties, and event locations.
Augmented Reality (AR): (Planned feature) Enables an immersive AR layer for route navigation within the community.
8. Automated Notifications and Reminders
Document Expiry: Automated reminders for document renewals or community meetings.
Maintenance Completion: Automated emails to homeowners when a maintenance request is marked as 'Done' with instructions for verification.
9. Chatbot Integration
Dialogflow-powered Chatbot: (Planned feature) Assists users in booking amenities, submitting maintenance requests, and accessing emergency information.


Technology Stack
Backend: Django (Python)
Frontend: HTML, CSS, Bootstrap, Tailwind CSS,jquery, JavaScript (for interactivity)

Database: PostgreSQL

Mapping: Leaflet.js for map integration
Real-Time Communication: Django Channels (for group chat and notifications)
Automated Email: Django's email system for notification alerts

Chatbot: Dialogflow (for chatbot integration, planned)

Installation
Prerequisites
Python 3.x
Django 3.x or higher
PostgreSQL
Node.js and npm (for managing frontend dependencies)

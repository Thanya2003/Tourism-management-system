Tourism Management System in PHP-----Installation Steps(Configuration)

1.Download and Unzip the file on your local system.
2.Copy tms folder and tms folder inside root directory (for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/HTML)

Database Configuration

Open PHPMyAdmin
Create Database tms
Import database tms.sql (available inside the zip package)
Open Your browser put inside browser “http://localhost/tms-php/tms”
Login Details for admin : 

Open Your browser put inside browser “http://localhost/tms-php/tms/admin”

Login Details for user: 

Open Your browser put inside browser “http://localhost/tms-php/tms”

Tourist Management
Add, Edit, Delete Tourists: Manage tourist information including names, contact details, and addresses.
View Tourist List: Display a list of all registered tourists.

Destination Management
Add, Edit, Delete Destinations: Manage details of tourism destinations, including names and descriptions.
View Destination List: Display all available destinations for tourists.

Booking Management
Create Bookings: Allow tourists to book accommodations at chosen destinations.
Manage Bookings: View, update, or cancel bookings as needed.
View Booking History: Track the booking history for individual tourists.

User Authentication
Login/Logout: Secure login and logout functionality for users.
User Roles: Different access levels for administrators and regular users.

Database Management
Normalized Database Structure: Efficiently designed database schema to prevent redundancy and ensure data integrity.
Database Backup and Restore: Functionality to backup and restore the database to prevent data loss.

Triggers
Automatic Updates: Implement triggers to automatically update related tables. For example, when a booking is made, a trigger can automatically update the availability status of the accommodation.
Auditing: Create triggers to log changes in important tables, such as logging when a tourist's details are updated.

Stored Procedures
Simplified Operations: Use stored procedures to handle complex operations, such as calculating the total price of a booking based on the number of nights and the price per night.
Consistency: Stored procedures ensure that business logic is centralized and consistent across the application.
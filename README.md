**RealEstate-PHP**

**Overview**
RealEstate-PHP is a web-based application for managing real estate listings and related administrative tasks. This system is built using PHP, JavaScript, and other frontend technologies like Bootstrap and 
jQuery. It offers a streamlined interface for real estate administrators to manage property listings, users, and other essential features.

**Features**
Admin Dashboard: Manage listings, users, and properties through an intuitive admin panel.
User Management: Add, edit, and delete user profiles.
Property Listings: Manage property details, photos, and information.
Rich Text Editor: Use TinyMCE for enhanced content management.
Responsive Design: Uses Bootstrap for a responsive, mobile-friendly interface.

**Installation**
**Clone the Repository:**

bash
git clone https://github.com/Kulbir33/Xenon-Stack.git
cd RealEstate-PHP

**Set Up Database:**
Import the database schema provided in the /database folder.
Configure the database connection in the config.php file located in the project root.

**Configure Web Server:**
Ensure you have PHP and a web server like Apache or Nginx installed.
Set up a virtual host to serve the project or use a local development environment like XAMPP.
Run the Application: Open your browser and navigate to the project’s URL (e.g., http://localhost/RealEstate-PHP).

**Folder Structure**

RealEstate-PHP/
│
├── admin/
│   ├── assets/           # JavaScript, CSS, and images for the admin panel
│   ├── views/            # Admin panel views
│   └── controllers/      # Backend logic for admin operations
│
├── js/                   # JavaScript files and libraries (TinyMCE, jQuery, etc.)
├── css/                  # CSS files for styling
└── index.php             # Entry point for the application

**Technologies Used**

Backend: PHP
Frontend: HTML, CSS, JavaScript (Bootstrap, jQuery)
Database: MySQL (or any relational database)

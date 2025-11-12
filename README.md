PG Life – Responsive Web Application for Finding PGs
A full-stack web application built to help students and working professionals find PG accommodations across major Indian cities.
Developed using HTML, CSS, JavaScript, PHP, and MySQL, it offers a responsive, user-friendly experience for exploring properties, viewing details, and managing interested listings.
-->Features
*Search PGs by City — Enter your city and explore available accommodations
*Property Listings — View property images, descriptions, amenities, and pricing
*Interested Feature — Save and view your favorite properties
*User Authentication — Secure signup/login with PHP sessions
*Fully Responsive — Works seamlessly across devices using Bootstrap
*Dashboard — Personalized space to manage interested PGs
*Database Integration — MySQL for managing users, cities, and properties

-->Project Structure
pg_life/
│
├── css/
│   ├── bootstrap.min.css
│   ├── common.css
│   ├── dashboard.css
│   ├── index.css
│   ├── property_detail.css
│   └── property_list.css
│
├── js/
│   ├── bootstrap.min.js
│   ├── common.js
│   ├── dashboard.js
│   ├── jquery.js
│   ├── property_detail.js
│   └── property_list.js
│
├── img/
│   ├── logo.png
│   ├── delhi.png
│   ├── mumbai.png
│   ├── bangalore.png
│   └── hyderabad.png
│
├── includes/
│   ├── database_connect.php
│   ├── footer.php
│   ├── header.php
│   ├── login_modal.php
│   └── signup_modal.php
│
├── api/
│   ├── handle_interested_dashboard.php
│   ├── login_submit.php
│   ├── signup_submit.php
│   └── toggle_interested.php
│
├── index.php
├── dashboard.php
├── property_list.php
├── property_detail.php
├── logout.php
└── readme

-->Tech Stack
1.Frontend:
HTML5
CSS3, Bootstrap4
JavaScript, jQuery
2.Backend:
PHP 7+
MySQL Database
3.Tools:
XAMPP (Apache + MySQL)
VS Code
Git & GitHub

# Online PG Website

This project is a web-based application for finding and managing Paying Guest (PG) accommodations. It provides a platform for users to search for PGs based on various criteria, view detailed information, and for administrators to manage the property listings.

## Features

Based on the project structure, the application includes the following features:

* **Property Listings:** Users can browse a list of available PGs (`property_list.php`).
* **Detailed View:** Users can click on a property to see more details (`property_detail.php`).
* **User Dashboard:** A dedicated dashboard for registered users (`dashboard.php`).
* **User Authentication:** Functionality for users to log in and log out (`logout.php` and likely a login system).
* **Backend API:** An `api` directory to handle data requests and backend logic.

## Tech Stack

The project is built using the following technologies:

* **Backend:** PHP
* **Frontend:** HTML, CSS, JavaScript
* **Database:** MySQL (inferred, as is standard with PHP)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need a local web server environment like [XAMPP](https://www.apachefriends.org/index.html) or [WAMP](https://www.wampserver.com/en/) which includes PHP, Apache, and MySQL.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/ayushpal1849/OnlinePGWebsite.git](https://github.com/ayushpal1849/OnlinePGWebsite.git)
    ```
2.  **Move to your server directory:**
    Move the cloned project folder into your web server's root directory (e.g., `htdocs` for XAMPP or `www` for WAMP).
3.  **Set up the database:**
    * Open your database management tool (like `phpMyAdmin` at `http://localhost/phpmyadmin`).
    * Create a new database.
    * Look for a `.sql` file in the repository (if one is provided) and import it into your new database.
4.  **Configure the database connection:**
    * Find the database connection file (it might be in the `includes` or `api` directory, often named `db_connect.php` or `config.php`).
    * Update the file with your local database credentials (host, username, password, and the database name you just created).
5.  **Run the application:**
    Open your web browser and navigate to `http://localhost/OnlinePGWebsite`.

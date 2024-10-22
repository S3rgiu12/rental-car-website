# Car Rental Website

Welcome to the Car Rental Website project! This repository contains the source code for a web application designed to manage the car rental process, built using Java, JSP, Servlets, HTML, CSS, and other web technologies.

## Project Overview

This web application allows users to browse and rent cars, manage bookings, and track rental history. The system also includes admin functionalities for managing the fleet of cars, rental periods, and users. The application features a responsive design and is structured into the following sections:
- **Home**: Overview of the services offered and available cars.
- **Browse Cars**: A list of cars available for rent with filtering options.
- **User Dashboard**: For registered users to view and manage their rentals.
- **Admin Dashboard**: For administrators to manage cars, users, and rental operations.

## Technologies Used

- **Frontend**: HTML, CSS (JSP), JavaScript
- **Backend**: Java, Java Servlet, JDBC
- **Database**: MySQL (managed with HeidiSQL)
- **Server**: Apache Tomcat
- **Tools**: Eclipse IDE, XAMPP

## Technologies Used


| Language/Tehnology  | Procentaj       |
|-------------------|-----------------|
| **Java**          | 50%             |
| **HTML**          | 25%             |
| **CSS**           | 25%             |

> **Note:** These percentages are automatically calculated by GitHub based on the project files.


## Features

- User authentication and authorization (login, register)
- Car rental booking system with real-time availability checks
- Admin panel to manage users, rentals, and car inventory
- Responsive layout for both desktop and mobile devices
- Database integration using JDBC for managing car inventory and user rentals

## How to Run Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/username/car-rental-website.git
    cd car-rental-website
    ```

2. Import the project into **Eclipse** as a Maven project.

3. Configure your **Tomcat server** in Eclipse:
    - Download and install [Tomcat](https://tomcat.apache.org/download-90.cgi).
    - Add the Tomcat server in Eclipse and configure the project to run on it.

4. Setup the database using **XAMPP** and **HeidiSQL**:
    - Start the **MySQL** server in XAMPP.
    - Create a database in HeidiSQL and import the provided SQL schema.

5. Configure the database connection in the project:
    - Update the database connection details in the `db.properties` or directly in the JDBC connection string in the Java files.

6. Run the project on the **Tomcat** server from Eclipse:
    ```bash
    Run -> Run on Server -> Apache Tomcat
    ```

## Future Improvements

- Add payment gateway integration for online payments.
- Implement a recommendation system for similar or popular cars.
- Create a mobile app version of the website for easier access.

## Contributing

Feel free to fork this repository and make changes. I welcome contributions, whether it's a bug fix, feature improvement, or other suggestion. You can open an issue or submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).


# Hospital Management System

## Project Overview

The Hospital Management System is a Java-based application designed to streamline hospital administrative tasks, including managing patient records, doctor information, and appointment scheduling. This system aims to improve the efficiency of hospital operations and enhance patient care.

## Features

- **Add Patient:** Register new patients with personal and medical details.
- **View Patients:** Access and manage patient records, including personal information and medical history.
- **View Doctors:** Display doctor information, including specialties, availability, and contact details.
- **Book Appointment:** Schedule appointments between patients and doctors, managing time slots and availability.
- **Check Appointment:** View and update appointment statuses for both patients and doctors.

## Technologies Used

- **Java:** Core programming language for developing application logic.
- **JDBC (Java Database Connectivity):** For connecting and interacting with the MySQL database.
- **MySQL:** Database management system used to store patient, doctor, and appointment data.

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/hospital-management-system.git
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd hospital-management-system
   ```
3. **Set Up the Database:**
   - Create a MySQL database named `hospital_management`.
   - Execute the provided SQL script (`database.sql`) to set up the required tables.

4. **Configure Database Connection:**
   - Update the database connection details (URL, username, password) in the Java code (`DatabaseConnection.java`).

5. **Compile and Run the Application:**
   ```bash
   javac Main.java
   java Main
   ```

## Usage

1. **Start the application.**
2. **Navigate through the menu** to add patients, view records, book or check appointments, and manage doctor information.
3. **Follow on-screen instructions** to complete the tasks efficiently.

## Future Enhancements

- Addition of a graphical user interface (GUI) for better user experience.
- Integration of email and SMS notifications for appointment reminders.
- Enhanced reporting features for patient and appointment analytics.

## Contributing

Contributions are welcome! Please create an issue or pull request if you wish to contribute.

